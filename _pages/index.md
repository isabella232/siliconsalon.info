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

Currently, there are no semiconductors designed specifically for crypto-wallets, forcing wallet manufacturers to cobble together solutions from what exists. Fortunately, that’s about to change, thanks to semiconductor manufacturers such as CrossBar and Tropic Square seeking to directly address the cryptocurrency,  digital identity & assets markets. 

The Silicon Salon drew together the community to discuss requirements in order to guide the direction of this new work and produce semiconductors that do exactly what the cryptocurrency market needs. It featured presentations from silicon manufacturers, crypto-wallet makers, and experts in the field about how semiconductor design can support cryptographic functionality, as well as discussion to allow everyone to have their say.

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

"The vendor is not going to change something that will trigger re-certification unless they have a large commitment from a big player like a phone manufacturer that actually wants that functionality. It's not necessarily a problem of the specs and standards not being there, it's unwillingness to implement the features quickly because of those market dynamics."
{: .notice--info}

"One of the big problems with this that I see is that the people who are making the major components for some of these products are not the people who are making the products. There's a disconnect between what the product requirements [are] and what the components can do because there is not a tight feedback loop."
{: .notice--info}

"Kerckhoff's principle is that the system has to be secure even if it is in enemy's hands, and the only thing you need to keep secret is the key. This is not really implemented in hardware; I think open-source software is on the good path to this kind of goal but on the hardware there's a lot of work to be done."
{: .notice--info}

## Discussions

Discussions were held on several major topics:

### 1. Pain points

Pain points describes the many problems with current semiconductor support for cryptography. This begins with support that is limited to Secure Enclaves and that doesn't include secp256k1, which is the elliptic curve used to implement Bitcoin and most other cryptocurrencies. Worse, what is supported is usually protected by NDAs and licensing restrictions, making it very hard for developers to even understand their choices. Even then, one-off cryptography, a lack of future proofing, a lack of available cryptographic talent, certification marks, and questions about market size can all make development very problematic.

There's also real question about what the future will bring, especially with worries about quantum computing — and even if those aren't real, concerns that current algorithms will be broken.

"I think there’s an inherent tension between certified & up-to-date."
{: .notice--info}

"Communication and collaboration is a pain point. One of the problems is that there's a general attitude of competition worldwide and I think it's worthwhile to emphasize that this has to be a collaborative effort. It's too big and complex for it to not be collaborative."
{: .notice--info}

### 2. Architectures

"To address the challenge of the 'crypto' evolving faster than chips can be made, I've wondered if it would be feasible to have essentially a "write once" FPGA-type of device."
{: .notice--info}

 "I think something like threshold signature is not to reduce reliance on hardware, but to enable *more* reliance on hardware. With single signature wallet, you have to store some amount of entropy off-wallet.  They typical failure is that the user forgets that off-wallet entropy  With multi-keys, you could store pieces in various locations, and have good security with decreased reliance on pin/passphrase in your head. It enables the hardware to shoulder more of the responsibility."
{: .notice--info}

"One of the most important things for a hardware wallet is to show the details of the transaction you are verifying."
{: .notice--info}

### 3. Boot, firmware & supply chain

"Firmware could be self-sovereign and the user could truly own [the chip they bought], instead of just "renting" it from the chip maker."
{: .notice--info}

"We are trying to move in the direction of zero black-box code, so we need details on the secure boot with no NDA."
{: .notice--info}

### 4. Cryptographic primitives, protocols & acceleration

"Really, you can't do any decent work without RAM. You can't do any decent work without a secure RNG; that has to be a mandatory thing, not a bag on the side that people deal with later."
{: .notice--info}

### 5. Threats & countermeasures
### 6. Edge topics
### 7. Building a secure infrastructure ecosystem

## Participants

Thanks to our sponsors and other participants:

![Sponsor List]({{ site.url }}{{ site.baseurl }}/assets/images/silicon-salon-sponsors.png)

## Chatham House Rules Apply

The Silicon Salon occured under the [Chatham House Rules](https://www.chathamhouse.org/about-us/chatham-house-rule), meaning that information could be freely used by all participants and statements could be quoted, but not attributed. A goal of Blockchain Commons is to give principals in the Web3 and blockchain space the ability to discuss potential interoperability, but to do so in a safe way.

_Silicon background image courtesy of  [Vecteezy](https://www.vecteezy.com/vector-art/344822-printed-circuit-board-vector-illustration)_.
