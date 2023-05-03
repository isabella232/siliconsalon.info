---
permalink: /salon4/
title: "Silicon Salon IV: May 3, 2023"
subtitle: "Filling in the Gaps"
layout: single
classes:
  - wide
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.25"
  overlay_image: /assets/images/silicon-salon-bare.jpg
  og_image: /assets/silicon-salon-4/images/silicon-salon4.jpg
---

## Overview

The fourth Silicon Salon, on May 3, 2023, offered a potpurri of
topics, **filling in some of the gaps** from our first year of
community work. This included presentations on how to ensure a
hardware wallet is avoiding key leakage and how we can better enable
biginteger operations in silicon. There was also a presentation and
discussion on a topic that goes back to Silicon Salon 1: integrating
the open-source ethos withe semiconductor work (and whether that's
possible at all!).

## Presentations

The fourth Silicon Salon featured [three
presentations](/salon4/presentations), from Andrew Poelstra, from Luke
Kenneth Casson Leighton, and from Cramium Labs.  There were also
question & answer sessions after each presentation.

<figure class="third">
	<a href="https://www.siliconsalon.info/salon4/presentations/#silicon-salon-overview"><img src="/assets/silicon-salon-4/presentations/silicon-salon-presentation.jpg"></a>
	<a href="https://www.siliconsalon.info/salon4/presentations/#andrew-poelstra-presentation"><img src="/assets/silicon-salon-4/presentations/poelstra-presentation.jpg"></a>
	<a href="https://www.siliconsalon.info/salon4/presentations/#luke-leighton-david-calderrwood-presentation"><img src="/assets/silicon-salon-4/presentations/libresoc-presentation.jpg"></a>
	<a href="https://www.siliconsalon.info/salon4/presentations/#cramium-labs-presentation"><img src="/assets/silicon-salon-4/presentations/cramium-presentation.jpg"></a>
</figure>

## Andrew Poelstra Presentation

View [the presentation](https://www.siliconsalon.info/salon4/presentations/#andrew-poelstra-presentation)

### Key Slides

<figure class="third">
	<a href="https://www.siliconsalon.info/salon4/presentations/"><img src="/assets/silicon-salon-4/presentations/poelstra-presentation-1.jpg"></a>
	<a href="https://www.siliconsalon.info/salon4/presentations/"><img src="/assets/silicon-salon-4/presentations/poelstra-presentation-2.jpg"></a>
	<a href="https://www.siliconsalon.info/salon4/presentations/"><img src="/assets/silicon-salon-4/presentations/poelstra-presentation-3.jpg"></a>
</figure>

### Key Quotes

_Signatures:_ "You can think of an elliptic curve (EC) signature
either ECDSA or Schnorr being a linear equation in two secret pieces
of data."
{: .notice--info}

_Key Exfil:_ "One immediate consequence of this is that if you don't
generate a new nonce and you reuse a nonce from a previous signature
you used, then someone can invert the matrix and solve this and do a
direct computation to get your secret key."
{: .notice--info}

_Anti-Exfil:_ "What's my solution? It takes the multisig premise here
which is that you have two participants and they mix their randomness
in together and they avoid biases."

### Key Links

* [Article](https://blog.blockstream.com/anti-exfil-stopping-key-exfiltration/) — [https://blog.blockstream.com/anti-exfil-stopping-key-exfiltration/](https://blog.blockstream.com/anti-exfil-stopping-key-exfiltration/)
* [Chosen Nonce Attack Workbook](https://github.com/stepansnigirev/chosen_nonce_demo/blob/master/HD_key.ipynb) - [https://github.com/stepansnigirev/chosen_nonce_demo/blob/master/HD_key.ipynb](https://github.com/stepansnigirev/chosen_nonce_demo/blob/master/HD_key.ipynb)

## Luke Leighton & David Calderwood Presentation

View [the presentation](https://www.siliconsalon.info/salon4/presentations/#luke-leighton-david-calderwood-presentation)

### Key Slides

<figure class="third">
	<a href="https://www.siliconsalon.info/salon4/presentations/"><img src="/assets/silicon-salon-4/presentations/libresoc-presentation-1.jpg"></a>
	<a href="https://www.siliconsalon.info/salon4/presentations/"><img src="/assets/silicon-salon-4/presentations/libresoc-presentation-2.jpg"></a>
	<a href="https://www.siliconsalon.info/salon4/presentations/"><img src="/assets/silicon-salon-4/presentations/libresoc-presentation-3.jpg"></a>
</figure>

### Key Quotes

_ISA Work:_ "Libre-SOC is researching and designing instructions which
will be proposed to the OpenPOWER ISA working group for official
inclusion in the Power ISA."
{: .notice--info}

_Instructions:_ "We want everything to be general purpose. We want
general purpose instructions that end up in mainstream compilers and
the mainstream software toolchains and libraries."
{: .notice--info}

_The Plan:_ "The initial concept was the usual 1-bit carry-in and
carry-out and then extend it to 64-bits. The result is that you get,
for free, a scalar vector arithmetic and you can do simple loops on
top of that and then you have Knuth algorithms D and M."
{: .notice--info}

_How It Works:__
"You're just outputting the second half of what is normally thrown
away as the carry-out."
{: .notice--info}

### Key Links

* [Biginteger Analysis](https://libre-soc.org/openpower/sv/biginteger/analysis/) — [https://libre-soc.org/openpower/sv/biginteger/analysis/](https://libre-soc.org/openpower/sv/biginteger/analysis/)
* [RFC ls003 Big Integer](https://libre-soc.org/openpower/sv/rfc/ls003/) — [https://libre-soc.org/openpower/sv/rfc/ls003/](https://libre-soc.org/openpower/sv/rfc/ls003/)
* [Open Titan](https://opentitan.org/book/hw/ip/otbn/doc/isa.html) — [https://opentitan.org/book/hw/ip/otbn/doc/isa.html](https://opentitan.org/book/hw/ip/otbn/doc/isa.html)

## Cramium Labs Presentation

View [the presentation](https://www.siliconsalon.info/salon4/presentations/#cramium-labs-presentation)

### Key Slides

<figure class="third">
	<a href="https://www.siliconsalon.info/salon4/presentations/"><img src="/assets/silicon-salon-4/presentations/cramium-presentation-1.jpg"></a>
	<a href="https://www.siliconsalon.info/salon4/presentations/"><img src="/assets/silicon-salon-4/presentations/cramium-presentation-2.jpg"></a>
	<a href="https://www.siliconsalon.info/salon4/presentations/"><img src="/assets/silicon-salon-4/presentations/cramium-presentation-3.jpg"></a>
</figure>

### Key Quotes

_The IP Question:_
"Does copyright apply to hardware? What about chips?"
{: .notice--info}

_Maskwork:_
"This is only one design artifact used in making a chip and it has its
own one-off right of its own."
{: .notice--info}

_Complexity of Silicon IP:_
"I don't expect you to absorb all these details. But there are many
stages and they involve varying third-party IP."
{: .notice--info}

_Copyleft Problems:_
"If you make a product that combines something that has a copyleft
license and a proprietary license, then in some cases the boundary of
licensing might expand to include the proprietary code."
{: .notice--info}

_An Open Question:_
"What is the purpose of open-source hardware? Why do we think it's
desirable?"
{: .notice--info}

_Cramium's Approach:_
"Our approach, subject to change, is that we're building a chip and
we're publishing an outbound CERN-OHL-W license."
{: .notice--info}

--------------

## Additional Discussions & Chat

Additional discussion focused on the question of Open Silicon.

## Participants

Thanks to our presenters and other participants!

* **Host:** [Blockchain Commons](https://www.blockchaincommons.com/)
* **Facilitators:** Christopher Allen, Bryan Bishop
* **Presenters:** [Andrew Poelstra](https://github.com/apoelstra), [Cramium Labs](https://www.cramiumlabs.com/), [Red Semiconductor](https://redsemiconductor.com/)
* **Sustaining Sponsors:** [Bitmark](https://bitmark.com/), [Chia](https://www.chia.net/), [CrossBar](https://www.crossbar-inc.com/), [Digital Contract Design](https://contract.design/), [Foundation](https://foundationdevices.com/), [Proxy](https://www.proxy.com/), [Unchained Capital](https://unchained.com/)

## Chatham House Rules Apply

The Silicon Salon occured under the [Chatham House
Rules](https://www.chathamhouse.org/about-us/chatham-house-rule),
meaning that information could be freely used by all participants and
statements could be quoted, but not attributed. A goal of Blockchain
Commons is to give principals in the Web3 and blockchain space the
ability to discuss potential interoperability, but to do so in a safe
way.

_Silicon background image courtesy of
[Vecteezy](https://www.vecteezy.com/vector-art/344822-printed-circuit-board-vector-illustration)_.
