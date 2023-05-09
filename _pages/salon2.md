---
permalink: /salon2/
title: "Silicon Salon II: September 14, 2022"
subtitle: "Secure Boot, Supply-Chain Security, and Firmware Upgrades"
layout: single
classes:
  - wide
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.25"
  overlay_image: /assets/images/silicon-salon-bare.jpg
  og_image: /assets/silicon-salon-2/images/silicon-salon2.jpg
---

## Overview

The second Silicon Salon, on September 14, 2022, again brought together principals from the crypto-wallet and semiconductor communities. This time, our focus was on **Secure Boot, Supply-Chain Security, and Firmware Upgrades**. We were seeking the answers to questions such as: How do we boot securely? How do we ensure firmware is secure? How do we update firmware? and How do we ensure the supply chain isn't at risk? Silicon cryptography is about more than just the design of a chip!

"This is the second Silicon Salon and we have dropped to the foundations."
{: .notice--info}

"A lot of this is about conversations between people who care."
{: .notice--info}

"We want to take the results from these group salons and learn to collaboratively engineer interoperable specifications."
{: .notice--info}

## Presentations

The first two-thirds of the Silicon Salon featured [presentations](/salon2/presentations/) by experts in the silicon, hardware, software, and cryptography fields, including Bunnie Studios, Cramium Labs, Foundation, Proxy, and the team behind Validated Lightning Signer. There were also question & answer sessions after each presentation.

<figure class="third">
	<a href="https://www.siliconsalon.info/salon2/presentations/#silicon-salon-overview"><img src="/assets/silicon-salon-2/presentations/silicon-salon-presentation.jpg"></a>
	<a href="https://www.siliconsalon.info/salon2/presentations/#bunnie-studios-presentation"><img src="/assets/silicon-salon-2/presentations/bunnie-studios-presentation.png"></a>
	<a href="https://www.siliconsalon.info/salon2/presentations/#cramium-presentation"><img src="/assets/silicon-salon-2/presentations/cramium-presentation.jpg"></a>
	<a href="https://www.siliconsalon.info/salon2/presentations/#foundation-presentation"><img src="/assets/silicon-salon-2/presentations/foundation-presentation.jpg"></a>
	<a href="https://www.siliconsalon.info/salon2/presentations/#proxy-presentation"><img src="/assets/silicon-salon-2/presentations/proxy-presentation.jpg"></a>
	<a href="https://www.siliconsalon.info/salon2/presentations/#vls-presentation"><img src="/assets/silicon-salon-2/presentations/vls-presentation.jpg"></a>
</figure>

## Bunnie Studios Presentation

View the [presentation including video, transcript, and slides](https://www.siliconsalon.info/salon2/presentations/#bunnie-studios-presentation).

### Key Slides

<figure class="third">
	<a href="/assets/silicon-salon-2/presentations/bunnie-studios-presentation-1.jpg"><img src="/assets/silicon-salon-2/presentations/bunnie-studios-presentation-1.jpg"></a>
	<a href="/assets/silicon-salon-2/presentations/bunnie-studios-presentation-2.jpg"><img src="/assets/silicon-salon-2/presentations/bunnie-studios-presentation-2.jpg"></a>
	<a href="/assets/silicon-salon-2/presentations/bunnie-studios-presentation-3.jpg"><img src="/assets/silicon-salon-2/presentations/bunnie-studios-presentation-3.jpg"></a>
</figure>

### Key Quotes

"Why are we doing a device and not just a  chip? If you want to protect the end-user secrets, then you have to think about the screens and keyboards being logged so this boils down to a secure I/O problem."
{: .notice--info}

"We want to make sure from the tips of your fingers, to the pixels hitting your eyes, that the entire path is trusted."
{: .notice--info}

"Our threat model is different. We don't trust our manufacturer. We don't trust the supply chain or anyone else's. Our goal is to empower user to control and protect their own hardware."
{: .notice--info}

## Cramium Labs Presentation 

View [the presentation including video, transcript, and slides](https://www.siliconsalon.info/salon2/presentations/#cramium-presentation).

### Key Slides

<figure class="third">
	<a href="/assets/silicon-salon-2/presentations/cramium-presentation-1.jpg"><img src="/assets/silicon-salon-2/presentations/cramium-presentation-1.jpg"></a>
	<a href="/assets/silicon-salon-2/presentations/cramium-presentation-2.jpg"><img src="/assets/silicon-salon-2/presentations/cramium-presentation-2.jpg"></a>
	<a href="/assets/silicon-salon-2/presentations/cramium-presentation-3.jpg"><img src="/assets/silicon-salon-2/presentations/cramium-presentation-3.jpg"></a>
</figure>

### Key Quotes

_Minimalism View:_ "Very small amounts of code. This code is just for loading the OEM bootloader once the OEM bootloader is loaded then, you don' t even use that. So there's absolutely no trust in the software that is loaded into this."
{: .notice--info}

_Lifecycle Progression:_ "The way we're thinking right now is only one-way lifecycle progressions that can only go forward. Once you go from chip to OEM, you can't rollback the chip for security reasons."
{: .notice--info}

_Full-feature Software:_ "The other option is to have full-feature software where everything here, like the cryptographic algorithms, are loaded into the chip bootloader. All the crypto functions get loaded during manufacturing."
{: .notice--info}

## Proxy Labs Presentation 

View [the presentation including video, transcript, and slides](https://www.siliconsalon.info/salon2/presentations/#proxy-presentation).

### Key Slides

<figure class="third">
	<a href="/assets/silicon-salon-2/presentations/proxy-presentation-1.jpg"><img src="/assets/silicon-salon-2/presentations/proxy-presentation-1.jpg"></a>
	<a href="/assets/silicon-salon-2/presentations/proxy-presentation-2.jpg"><img src="/assets/silicon-salon-2/presentations/proxy-presentation-2.jpg"></a>
	<a href="/assets/silicon-salon-2/presentations/proxy-presentation-3.jpg"><img src="/assets/silicon-salon-2/presentations/proxy-presentation-3.jpg"></a>
</figure>

### Key Quotes

"One of the attack vectors we have seen is that if you can't compromise the code or inject code running on the MCU for example, you can often take the MCU off and introduce an MCU that already has compromised code on it."
{: .notice--info}

"A lot of the MCU code verification relies on code running on the MCU itself and it's subject to silicon vendor bugs, glitch attacks, etc."
{: .notice--info}

"We're interested in authenticity check using WebBluetooth and WebNFC so that you don't have to rely on an app you can't inspect."
{: .notice--info}

## Foundation Devices Presentation 

View [the presentation including video, transcript, and slides](https://www.siliconsalon.info/salon2/presentations/#foundation-presentation).

### Key Slides

<figure class="third">
	<a href="/assets/silicon-salon-2/presentations/foundation-presentation-1.jpg"><img src="/assets/silicon-salon-2/presentations/foundation-presentation-1.jpg"></a>
	<a href="/assets/silicon-salon-2/presentations/foundation-presentation-2.jpg"><img src="/assets/silicon-salon-2/presentations/foundation-presentation-2.jpg"></a>
	<a href="/assets/silicon-salon-2/presentations/foundation-presentation-3.jpg"><img src="/assets/silicon-salon-2/presentations/foundation-presentation-3.jpg"></a>
</figure>

### Key Quotes

"We didn't want to rely on factory provisioning tools from other vendors. So the first thing we do is load a test bootloader onto the MCU and we run through a series of hardware tests to make sure everything was assembled properly, like testing the screen controller, the secure element, making sure we can communicate with everything."
{: .notice--info}

"One of the important security steps is that we have a supply chain secret that is copied to Passport."
{: .notice--info}

"[Our] pairing secret is used to prove the secure element and MCU are a matched set. This is to prevent an attacker from swapping out device components."
{: .notice--info}

## Validated Lightning Signer Presentation 

View [the presentation including video, transcript, and slides](https://www.siliconsalon.info/salon2/presentations/#vls-presentation).

### Key Slides

<figure class="third">
	<a href="/assets/silicon-salon-2/presentations/vls-presentation-1.jpg"><img src="/assets/silicon-salon-2/presentations/vls-presentation-1.jpg"></a>
	<a href="/assets/silicon-salon-2/presentations/vls-presentation-2.jpg"><img src="/assets/silicon-salon-2/presentations/vls-presentation-2.jpg"></a>
	<a href="/assets/silicon-salon-2/presentations/vls-presentation-3.jpg"><img src="/assets/silicon-salon-2/presentations/vls-presentation-3.jpg"></a>
</figure>

### Key Quotes

"The basic concept of VLS is to not have the private keys or other secrets in the online node itself."
{: .notice--info}

"Originally we were thinking about using the VLS software inside a hardware security module to secure an enterprise-scale lightning node. As we went on, we discovered other cases where inexpensive consumer devices could provide custody to end users and this was important for different reasons."
{: .notice--info}

"Our wish list items that would significantly improve security include tamper-proof hardware which can protect us when the physical security of the device is compromised."
{: .notice--info}

## Additional Discussions

Discussions were held on our planned three major topics:

### Boot

"What should the bootloader do? Should it be very minimum code that only opens up the communication port and OEM will take care of everything else? Should it do all the crypto engines at the API level, and let the OEM do more of the I/Os, displays, and customizations? Or should it be something in between?"
{: .notice--info}

"Trusted and untrusted implies a binary way of thinking about the world which may not be how it really works."
{: .notice--info}

"Some of the struggle is how to create logic that deals with any physical attack. Byzantine Fault Tolerance tries to do that by saying everything is unreliable and let's address it with logic. But there is an importance to physical security on the MCU itself.
{: .notice--info}

[Discuss Topic](https://github.com/BlockchainCommons/Airgapped-Wallet-Community/discussions/90){: .btn .btn--info}
{: .text-right}

### Firmware

"We're attaching to an SE chip that wasn't really designed for our use case. I would hope that we can have an SE from Tropic Square or Crossbar that is designed for the use cases that we're interested in and not ones that the payment card industry is interested in."
{: .notice--info}

"When you deal with Apple, you do what they tell you to do. You don't get a lot of leverage. They decide how their platform shall be used and they decide all the bits if you want to participate in it, and that applies to their payment platform as well. But on the other hand, they can dictate silicon features that go into future chips and some of that does end up trickling down and being available to the rest of us."
{: .notice--info}

[Discuss Topic](https://github.com/BlockchainCommons/Airgapped-Wallet-Community/discussions/90){: .btn .btn--info}
{: .text-right}

### Supply Chain

"There's a lot of details in the supply chain and its complexity. Where are the components? What about proof of custody along the way to the factory? Who is on the factory floor at the factory?"
{: .notice--info}

"We try to track all of the pieces we're putting into the software supply chain so that we know at least how big the attack surface is. Realistically these tools are so complicated that I can't say with any confidence that we know there are no backdoors in any given tool, but at least we have enumerated the tools and the problems we could have with them."
{: .notice--info}

"One thing brought up as a question is whether there's any standard way for doing supply chain authentication, rather than everyone doing their own."
{: .notice--info}

"Having a cryptographically strong unique ID is better than a scary plaintext serial number. The flip side of this is that securing your supply chain secret is hard because you need it on the manufacturing line, and how do you protect that?"
{: .notice--info}

[Discuss Topic](https://github.com/BlockchainCommons/Airgapped-Wallet-Community/discussions/90){: .btn .btn--info}
{: .text-right}

## Participants

Thanks to our participants, including:

![Sponsor List]({{ site.url }}{{ site.baseurl }}/assets/silicon-salon-2/images/silicon-salon2-sponsors.png)

* **Host:** [Blockchain Commons](https://www.blockchaincommons.com/)
* **Facilitators:** Christopher Allen, Bryan Bishop
* **Presenters:** [Bunnie Studios](https://www.bunniestudios.com/), [Cramium Labs](https://www.cramiumlabs.com/), [Foundation](https://foundationdevices.com/), [Proxy](https://www.proxy.com/), [The VLS Team](https://gitlab.com/lightning-signer/validating-lightning-signer)
* **Sustaining Sponsors:** [Bitmark](https://bitmark.com/), [Blockchainbird](https://github.com/blockchainbird/bird), [Chia](https://www.chia.net/), [CrossBar](https://www.crossbar-inc.com/), [Foundation](https://foundationdevices.com/), [Proxy](https://www.proxy.com/), [Unchained Capital](https://unchained.com/)

## Chatham House Rules Apply

The Silicon Salon occured under the [Chatham House Rules](https://www.chathamhouse.org/about-us/chatham-house-rule), meaning that information could be freely used by all participants and statements could be quoted, but not attributed. A goal of Blockchain Commons is to give principals in the Web3 and blockchain space the ability to discuss potential interoperability, but to do so in a safe way.

_Silicon background image courtesy of  [Vecteezy](https://www.vecteezy.com/vector-art/344822-printed-circuit-board-vector-illustration)_.
