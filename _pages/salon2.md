---
permalink: /salon2/
title: "Silicon Salon II: September 14, 2022"
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

The second Silicon Salon, on September 14, 2022, again brought together principals from the crypto-wallet and semiconductor communities. This time, our focus was on secure boot, supply-chain security, and firmware upgrades. We were seeking the answers to questions such as: How do we boot securely? How do we ensure firmware is secure? How do we update firmware? and How do we ensure the supply chain isn't at risk? Silicon cryptography is about more than just the design of a chip!

"A lot of this is about conversations between people who care."
{: .notice--info}

"We want to take the results from these group salons and learn to collaboratively engineer interoperable specifications."
{: .notice--info}

## Presentations

The first two-thirds of the Silicon Salon featured [presentations](/salon2/presentations/) by experts in the silicon, hardware, software, and cryptography fields, including Bunnie Studios, Foundation Devices, Proxy, Tropic Square, and the team behind Validated Lightning Signer. There were also question & answer sessions after each presentation.

<figure class="third">
	<a href="https://www.siliconsalon.info/salon2/presentations/"><img src="/assets/salon2/presentations/silicon-salon-presentation.jpg"></a>
	<a href="https://www.siliconsalon.info/salon2/presentations/"><img src="/assets/salon2/presentations/proxy-presentation.jpg"></a>
	<a href="https://www.siliconsalon.info/salon2/presentations/"><img src="/assets/salon2/presentations/libresoc-presentation.jpg"></a>
	<a href="https://www.siliconsalon.info/salon2/presentations/"><img src="/assets/salon2/presentations/crossbar-presentation.jpg"></a>
	<a href="https://www.siliconsalon.info/salon2/presentations/"><img src="/assets/salon2/presentations/tropicsquare-presentation.jpg"></a>
</figure>

### Bunnie Studios Presentation Key Quotes

"Why are we doing a device and not just a  chip? If you want to protect the end-user secrets, then you have to think about the screens and keyboards being logged so this boils down to a secure I/O problem."
{: .notice--info}

"We want to make sure from the tips of your fingers, to the pixels hitting your eyes, that the entire path is trusted."
{: .notice--info}

"Our threat model is different. We don't trust our manufacturer. We don't trust the supply chain or anyone else's. Our goal is to empower user to control and protect their own hardware."
{: .notice--info}

### Cramium Labs Presentation Key Quotes

_Minimalism View:_ "Very small amounts of code. This code is just for loading the OEM bootloader once the OEM bootloader is loaded then, you don' t even use that. So there's absolutely no trust in the software that is loaded into this."
{: .notice--info}

_Lifecycle Progression:_ "The way we're thinking right now is only one-way lifecycle progressions that can only go forward. Once you go from chip to OEM, you can't rollback the chip for security reasons."
{: .notice--info}

_Full-feature Software:_ "The other option is to have full-feature software where everything here, like the cryptographic algorithms, are loaded into the chip bootloader. All the crypto functions get loaded during manufacturing."

### Proxy Labs Presentation Key Quotes

## Additional Discussions

Discussions were held on several major topics:

### Supply Chain

"We try to track all of the pieces we're putting into the software supply chain so that we know at least how big the attack surface is. Realistically these tools are so complicated that I can't say with any confidence that we know there are no backdoors in any given tool, but at least we have enumerated the tools and the problems we could have with them."
{: .notice--info}

[Discuss Topic](https://github.com/BlockchainCommons/Airgapped-Wallet-Community/discussions/93){: .btn .btn--info}
{: .text-right}

### Bootloader

"What should the bootloader do? Should it be very minimum code that only opens up the communication port and OEM will take care of everything else? Should it do all the crypto engines at the API level, and let the OEM do more of the I/Os, displays, and customizations? Or should it be something in between?"
{: .notice--info}

## Participants

[redo]

Thanks to our participants, including:

![Sponsor List]({{ site.url }}{{ site.baseurl }}/assets/silicon-salon-1/images/silicon-salon-sponsors.png)

* **Host:** [Blockchain Commons](https://www.blockchaincommons.com/)
* **Facilitators:** Christopher Allen, Bryan Bishop
* **Presenters:** [CrossBar](https://www.crossbar-inc.com/), [Proxy](https://www.proxy.com/), [Tropic Square](https://tropicsquare.com/), [Libre-SOC](https://libre-soc.org/)
* **Sustaining Sponsors:** [Bitmark](https://bitmark.com/), [Blockchainbird](https://github.com/blockchainbird/bird), [CrossBar](https://www.crossbar-inc.com/), [Foundation Devices](https://foundationdevices.com/), [Proxy](https://www.proxy.com/), [Unchained Capital](https://unchained.com/)

## Chatham House Rules Apply

The Silicon Salon occured under the [Chatham House Rules](https://www.chathamhouse.org/about-us/chatham-house-rule), meaning that information could be freely used by all participants and statements could be quoted, but not attributed. A goal of Blockchain Commons is to give principals in the Web3 and blockchain space the ability to discuss potential interoperability, but to do so in a safe way.

_Silicon background image courtesy of  [Vecteezy](https://www.vecteezy.com/vector-art/344822-printed-circuit-board-vector-illustration)_.
