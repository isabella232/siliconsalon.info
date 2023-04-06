---
permalink: /proposals/
title: "Call for Proposals"
header:
  overlay_color: "#000"
  overlay_filter: "0.25"
  overlay_image: /assets/images/silicon-salon-bare.jpg
  og_image: /assets/images/silicon-salon-call.jpg
classes:
- wide
redirect_from:
- /contribute/
---

Silicon Salon 4 is planned for May 3, 2023. Future Silicon Salons are tentatively scheduled for July 26 and October 25. Propose a presentation now!
{: .notice--success}

The Silicon Salon is returning on a quarterly basis, with virtual workshops scheduled for [January (completed)](https://www.siliconsalon.info/salon3/), May, July, and October of this year. We will be bringing together digital wallet developers, semiconductor manufacturers, and academics. Our ultimate objective: to ensure that the next generation of cryptographic semiconductors meets everyones' needs, advancing the entire cryptography industry. You can keep up to date with this and future Salons by signing up for the [Silicon Salon announcement list](/subscribe/).

_We want you_ to make a presentation about your unique experiences in the field, whether you're producing semiconductors with an eye toward cryptography support, working on digital-asset wallets, or researching and publishing about cryptographic capabilities. We want to highlight cutting-edge research, innovative technologies, and real-world applications that are shaping the future of silicon-based security architectures. 

For [Silicon Salon 4 on May 3rd](https://www.eventbrite.com/e/silicon-salon-4-tickets-558196208887), we are currently planning the following events:

* **Anti-Exfil: Preventing Key Exfiltration Through Signature Nonce Data**. (Andrew Poelstra.) Secure nonce generation is a critical part of generating EC signatures, such as ECDSA or BIP-340 "Schnorr" signatures. If a hardware wallet fails to generate these nonces uniformly at random, then key leakage will occur, in extreme cases in as few as 2 signatures. Furthermore, it is possible for a malicious implementor to exfiltrate key data this way, and such an attack would be practically impossible to detect. This talk introduces a protocol we term "anti-exfil", in which a hardware wallet and host computer engage in a 2-round interactive protocol to produce a signature, in which the host computer is able to provide randomness which it can verify was included in the signature nonce. Therefore, unless both the host computer and hardware wallet are simultaneously compromised, this attack vector is entirely closed.
* **Scalar and Vector Draft Biginteger instructions for the Power ISA** (Luke Leighton & David Calderwood). Most RISC ISAs are missing instructions that allow for easy chaining to create Vector results for biginteger operation. The lack of good arbitrary-length Scalable-Vector biginteger instructions leads to the unfortunate conclusion that Hard Macros are the best way to implement big-integer cryptographic applications. Unfortunately that "bakes in" implementations in a fast-moving ecosystem. This presentation describes the need for 3-in 2-out instructions that greatly simplify biginteger operations as a key strategic requirement for semiconductor design.
* **Open Hardware Discussion.** An open discussion on applying open-source principles to hardware.

We are looking particularly for other talks that might complement Andrew's work, such as discussions of signatures, of nonces, or of security protocols, however we are always open to any discussions that can bridge software requirements and hardware designs.

Here are some of our best presentations from the recent Silicon Salons:

<figure class="third">
  <a href="https://www.youtube.com/watch?v=ZCZ_dwui-X0"><img src="/assets/silicon-salon-2/presentations/foundation-presentation.jpg"></a>
  <a href="https://www.youtube.com/watch?v=r4PxckECvpo"><img src="/assets/silicon-salon-3/presentations/cramium-presentation.jpg"></a>
  <a href="https://www.youtube.com/watch?v=liMA-8zmu1E"><img src="/assets/silicon-salon-3/presentations/sreedhar-presentation.jpg"></a>
</figure>

Become a part of this collaboration by proposing your own presentation for a future Silicon Salon, covering topics such as:

* Cryptographic algorithms and protocols
* Semiconductor capabilities for cryptography
* Digital wallet requirements and design
* Cryptography in IoT and edge devices

To propose a presentation, mail us at [team@blockchaincommons.com](mailto:team@blockchaincommons.com) and tell us:

1. The title of the presentation.
2. A summary of what your presentation will be about.
3. A summary of how this topic focuses on semiconductor capabilities, wallet requirements, or other related topics.
4. The name of the presenter(s). 
5. A description of who they are and how they or their company have the expertise, capability, or reach to benefit the Silicon Salon conversation.

Final presentations should be about ten-to-fifteen minutes long, supported by a slidedeck, which you will present in Zoom on the date of the salon. Be prepared for a Q&A afterward and to participate in broader discussions.

We encourage submissions from a wide range of perspectives and backgrounds, and welcome interdisciplinary approaches that bridge the gap between academia and industry. By participating in the Silicon Salon, you will have the opportunity to network with top professionals in the field, exchange ideas and insights, and make a lasting impact on the future of cryptography and digital assets.

Join us in shaping the future of cryptography and digital assets at the Silicon Salon!

_Silicon Salon is chaired by Christopher Allen, the co-author of the TLS standard and the founder of [Rebooting the Web of Trust](https://www.weboftrust.info/), which has to-date published over 60 papers and projects on the future of decentralized identity. He is also the founder of [Blockchain Commons](https://www.blockchaincommons.com/), a not-for-profit public-benefit corporation intended to continue that collaboration._
