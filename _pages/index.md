---
permalink: /
title: "Silicon Salon I: June 1, 2022"
layout: single
classes:
  - wide
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.25"
  overlay_image: /assets/images/silicon-salon-bare.jpg

---

## Overview

Currently, there are no semiconductors designed specifically for crypto-wallets, forcing wallet manufacturers to cobble together solutions from what exists. Fortunately, that’s about to change, thanks to semiconductor manufacturers such as CrossBar and Tropic Square, who are seeking to directly address the cryptocurrency, digital identity & assets markets. 

The Silicon Salon drew together a variety of principals in the community to discuss requirements that can guide the direction of this new work and produce semiconductors that do exactly what the cryptocurrency market needs. It featured presentations from silicon manufacturers, crypto-wallet makers, and experts in the field about how semiconductor design can support cryptographic functionality, as well as discussion that allowed everyone to have their say.

"Financial incentives are failing to create a robust secure infrastructure, and this is at all levels: not just the hardware but wallets and the network stack that we need for all of our stuff to function."
{: .notice--info}

"Crypto wallets [are] using semiconductors that are largely designed not for you but designed for other purposes. Look at a typical MCU in a wallet, you probably have a hundred such MCUs in your house. They were designed for those purposes, not for cryptocurrency."
{: .notice--info}

## Presentations

The first hour of the Silicon Salon featured [presentations](/presentations/) by experts in the silicon, hardware, software, and cryptography fields, including Christopher Allen, Bryan Bishop, CrossBar, Proxy, Tropic Square, and Libre-SOC.

<figure class="third">
	<a href="/assets/silicon-salon-1/presentations/silicon-salon-presentation.pdf"><img src="/assets/silicon-salon-1/presentations/silicon-salon-presentation.jpg"></a>
	<a href="/assets/silicon-salon-1/presentations/proxy-presentation.pdf"><img src="/assets/silicon-salon-1/presentations/proxy-presentation.jpg"></a>
	<a href="https://www.youtube.com/watch?v=us061o4PBZs"><img src="/assets/silicon-salon-1/presentations/libresoc-presentation.jpg"></a>
	<a href="/assets/silicon-salon-1/presentations/crossbar-presentation.pdf"><img src="/assets/silicon-salon-1/presentations/crossbar-presentation.jpg"></a>
	<a href="/assets/silicon-salon-1/presentations/tropicsquare-presentation.pdf"><img src="/assets/silicon-salon-1/presentations/tropicsquare-presentation.jpg"></a>
</figure>

### CrossBar Key Quotes

"There are really quite different cultures here. In chips, it's super expensive to develop a chip. Rather than thinking in terms of cost to acquire a customer, we think of the tooling cost and our key metric is gross margin."
{: .notice--info}

### Proxy Key Quotes

"Since we're so limited in space and power, we work with a high degree of integration, and we're not dealing with discrete components often. We are talking about multi-chip packages which are highly integrated, to save on space and power and routing area on the circuit boards."
{: .notice--info}

"The vendor is not going to change something that will trigger re-certification unless they have a large commitment from a big player like a phone manufacturer that actually wants that functionality. It's not necessarily a problem of the specs and standards not being there, it's unwillingness to implement the features quickly because of those market dynamics."
{: .notice--info}

"One of the big problems with this that I see is that the people who are making the major components for some of these products are not the people who are making the products. There's a disconnect between what the product requirements [are] and what the components can do because there is not a tight feedback loop."
{: .notice--info}

"Let's find ways to build architectures where some of the existing applications can co-exist with some of the new stuff being developed by crypto-wallets."
{: .notice--info}

### Tropic Square Key Quotes

"There is a problem in the market of chips that you can't buy a transparent chip so you have to trust the vendor and you have little to no visibility to implementation."
{: .notice--info}

"Kerckhoff's principle is that the system has to be secure even if it is in enemy's hands, and the only thing you need to keep secret is the key. This is not really implemented in hardware; I think open-source software is on the good path to this kind of goal but on the hardware there's a lot of work to be done."
{: .notice--info}

"Security in obscurity is the existing status quo where you rely on the secrecy of the implementation and all these processes, which basically has a side-effect of keeping weak designs in production."
{: .notice--info}

### Libre-SOC Key Quotes
"The challenges that a crypto-wallet ASIC faces is first and foremost that there is a massive industry-wide paranoid 5-layer-deep NDA chain."
{: .notice--info}

"Use libre VLSI tools because you want people to be able to independently verify your GDS-II files, then you can't rely on a proprietary toolchain. At the moment you would be limited to about 130 nm, which you can use to achieve 700 Mhz which is not that bad."
{: .notice--info}

## Discussions

Discussions were held on several major topics:

### 1. Pain points

Pain points describes the many problems with current semiconductor support for cryptography. This begins with support that is limited to Secure Enclaves and that doesn't include secp256k1, which is the elliptic curve used to implement Bitcoin and most other cryptocurrencies. Worse, what is supported is usually protected by NDAs and licensing restrictions, making it very hard for developers to even understand their choices. Even then, one-off cryptography, a lack of future proofing, a lack of available cryptographic talent, certification marks, and questions about market size can all make development very problematic.

There are also real question about what the future will bring, especially with worries about quantum computing — and even if those aren't real, concerns that current algorithms will be broken in other ways, including the relentless advance of time (and thus technology).

"I think there’s an inherent tension between certified & up-to-date."
{: .notice--info}

"Communication and collaboration is a pain point. One of the problems is that there's a general attitude of competition worldwide and I think it's worthwhile to emphasize that this has to be a collaborative effort. It's too big and complex for it to not be collaborative."
{: .notice--info}

### 2. Architectures

How do we establish the next generation of root-of-trust in secure silicon? There have been discussions about the nature of Secure Enclave–only architectures. Perhaps what we really need to do is more securely store keys of different types. There are many other options, such as only putting accelerators in silicon or creating devices with multiple Secure Enclaves.

However, if we’re looking at the future over the next 5-10 years, perhaps the world is moving more toward collaborative key generation through secure multi-party computation and threshold signatures. Does that lower our reliance on needing keys and signing in trusted secure hardware? 

"One of the challenges of architectures is that they have to fit into a larger ecosystem of chips and boards and then off to networks and things of that nature."
{: .notice--info}

"People ask is it in software, is it in hardware, but really it's a contiguous spectrum. You could think of a state machine that has registers and it is connected to logic, or you have shared memory, or you could have microcode, or a real CPU, or a CPU with a bus fabric that doesn't have a connection to the secret, but you have some memory protection unit or you can do everything in software."
{: .notice--info}

"To address the challenge of the 'crypto' evolving faster than chips can be made, I've wondered if it would be feasible to have essentially a "write once" FPGA-type of device."
{: .notice--info}

"It's not that there's a particular high security low level path between the things ... it's nice if those buttons don't go through untrusted elements on the way to the SE. The shorter the path, the better from a security standpoint."
{: .notice--info}

 "I think something like threshold signature is not to reduce reliance on hardware, but to enable *more* reliance on hardware. With single signature wallet, you have to store some amount of entropy off-wallet.  They typical failure is that the user forgets that off-wallet entropy  With multi-keys, you could store pieces in various locations, and have good security with decreased reliance on pin/passphrase in your head. It enables the hardware to shoulder more of the responsibility."
{: .notice--info}

"These often run in passive power environments like your credit card for example has a JavaCard SE in it but it's not powered, it's only powered by the NFC field of the reader. So essentially your processing call will start and stop based on available power from being in the NFC field and being removed, and it needs to persist its entire state and re-hydrate when you put it back into a power field. It's a little bit different to code for.
{: .notice--info}

### 3. Boot, Firmware & Supply Chain

Secure silicon doesn't exist on its own. There are also bootloaders and firmware and a whole supply-chain. The supply-chain needs authentication and the code needs auditability and verifiability. Black-box code can make all of this problematic. Do attestations or lists of trusted manufacturers help to solve these problems? 

This core issue also led to discussions of the problem of authentication, in large part due to Google moving away from passwords and toward device sign-ins. Uploading keys into HSMs and using OCAPs may both offer solutions to some of these problems. 

"Firmware could be self-sovereign and the user could truly own [the chip they bought], instead of just "renting" it from the chip maker."
{: .notice--info}

"We are trying to move in the direction of zero black-box code, so we need details on the secure boot with no NDA."
{: .notice--info}

"You have to always look where are people able to lock you in in maybe ways that you’re not anticipating."
{: .notice--info}

"I am surprised frankly how much people accept entropy from unknown source."
{: .notice--info}

"I am nervous about a push that is anti-self-sovereign like on identity and authentication. What I suspect will happen is: well here is a trusted set of manufacturers where they are generating the keys for the user, and we think it's a security vulnerability if a user is generating and uploading their own key to the HSM."
{: .notice--info}

"It's often these little small things that get you in the end. With twitter, lots of people were saying "oh great twitter open APIs, we're building companies on top of it!", but then there's that one little API call which is "please use my API token" and they basically started limiting that and shutdown that entire ecosystem. So you have to always look where are people able to lock you in in ways that you're not anticipating."
{: .notice--info}

"one of the things we haven't talked about ... is external memory encryption, any sort of external flash chip being able to support on-the-fly real encryption and decryption of all memory access. That often becomes a weakpoint. Sometimes there's sensitive data that needs to go into external memory due to size limitations (e.g. biometric templates), sometimes there is execute-in-place (XIP) code that lives in external flash, and it's not often covered by memory protection that your MCU or SE might offer.
{: .notice--info}

### 4. Cryptographic primitives, protocols & acceleration

The question of cryptographic primitives mainly focuses on what sorts of encryption and what curves should be supported by silicon, including issues of whether the cryptography will be ZK-friendly and quantum-attack resistant. One of the biggest problems is the lack of support for secp256k1, escpecially as Schnorr on secp becomes more important. There was also interest in supporting Ed25519/EdDSA as well as emerging technologies such as ChaCha20 and AES 512. 

One of the concerns going forward is that the lifespan of these algorithms is always limited, and by the time something has gone through full certification, half of its lifespan might already be gone!

"How many of the algorithms on this page are based on big-integer arithmetic and modulo? I think almost all of them."
{: .notice--info}

"Really, you can't do any decent work without RAM. You can't do any decent work without a secure RNG; that has to be a mandatory thing, not a bag on the side that people deal with later."
{: .notice--info}

"Random numbers are always an after thought, and they can’t be an afterthought."
{: .notice--info}

"Using a randomness in a nonce is very different from using randomness for a key."
{: .notice--info}

### 5. Threats & Countermeasures

Threats cover issues of secure input and output, supply-chain security, memory privacy, and side-chain resistance. Countermeasures discuss how to resolve threats, including making things tamper-evident (so that tampering can be seen), tamper-resistant (so that tampering can be made more difficult), and tamper-proof (so that tampering can't occur, which may be an impossible case). 

(This and later topics got more limited discussion at the salon due to time limitations.)

"I’ve taken to calling this “understandable security” rather than “proofs of security”: if you have something that you know has limitations and everyone knows what those are and you can work around those, then that’s better than a thing that nobody actually knows how it works at all."
{: .notice--info}

### 6. Edge topics

Our brief discussion of edge cases touched on issues that didn't easily fit into another topic. Briefly covered topics include why cryptographic keys can't be used for a variety of purposes, how we can do smart-contract calculation with accelerators, how to improve threat modeling and adversarial analysis, what the emergant security models are in a variety of adjacent fields, and how multisig is moving us away from single points of failure. There are a _lot_ of varied topics that are of relevance when considering the next generation of silicon design!

"Why can’t I use my cryptocurrency key to secure my end-to-end encryption with Signal, instead of having that be totally orthagonal?"
{: .notice--info}

### 7. Building a secure infrastructure ecosystem

Ultimately, we have to ask who we're missing from our discussions, and how we can bring them in, to improve the cross-discussion of requirements, and ultimately the interoperability of our field. We'd like to see more cryptographers and to have more presentations by a variety of people next time we host a Silicon Salon.

There were also interesting discussions about whether we can cooperate as a field, trading peer review with each other, for example, to create a more robust ecosystem.

"What does “ecosystem” mean? To me it’s much more than cryptocurrency and Web3."
{: .notice--info}

"Please consider User Experience, even if your expertise is far from the user level."
{: .notice--info}

## Participants

Thanks to our sponsors and other participants:

![Sponsor List]({{ site.url }}{{ site.baseurl }}/assets/images/silicon-salon-sponsors.png)

## Chatham House Rules Apply

The Silicon Salon occured under the [Chatham House Rules](https://www.chathamhouse.org/about-us/chatham-house-rule), meaning that information could be freely used by all participants and statements could be quoted, but not attributed. A goal of Blockchain Commons is to give principals in the Web3 and blockchain space the ability to discuss potential interoperability, but to do so in a safe way.

_Silicon background image courtesy of  [Vecteezy](https://www.vecteezy.com/vector-art/344822-printed-circuit-board-vector-illustration)_.
