---
permalink: /salon3/
title: "Silicon Salon III: January 18, 2023"
subtitle: "Investigating New Silicon-Based Cryptographic Functionality"
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

The third Silicon Salon, on January 18, 2023, expanded our community
of crypto-wallet developers and semiconductor manufacturers to also
include the halls of academia.

Once again, the community came together to discuss the requirements
and realities of semiconductor design, but this time the focus was on
**new silicon-logic-based cryptographic functionality** as well as new
opportunities for semiconductor acceleration, such as Multi-Party
Computation (MPC) and ZK-proofs.

"What we’re trying to explore today is silicon logic–based
cryptographic functionality. What are the opportunities for
semiconductor acceleration of cryptography, as MPC and ZKP
technologies are beginning to be deployed?"
{: .notice--info}

## Presentations

The third Silicon Salon featured [three
presentations](/salon3/presentations), from Bunnie Studios and Cramium
Labs, as well as cryptographer Kavya Sreedhar. There were also
question & answer sessions after each presentation.

<figure class="third">
	<a href="https://www.siliconsalon.info/salon3/presentations/"><img src="/assets/silicon-salon-3/presentations/silicon-salon-presentation.jpg"></a>
	<a href="https://www.siliconsalon.info/salon3/presentations/"><img src="/assets/silicon-salon-3/presentations/bunnie-studios-presentation.jpg"></a>
	<a href="https://www.siliconsalon.info/salon3/presentations/"><img src="/assets/silicon-salon-3/presentations/cramium-presentation.jpg"></a>
	<a href="https://www.siliconsalon.info/salon3/presentations/"><img src="/assets/silicon-salon-3/presentations/sreedhar-presentation.jpg"></a>
</figure>

## Cramium Labs Presentation 

View [the video](https://www.youtube.com/watch?v=r4PxckECvpo).

### Key Slides

<figure class="third">
	<a href="https://www.siliconsalon.info/salon3/presentations/"><img src="/assets/silicon-salon-3/presentations/cramium-presentation-1.jpg"></a>
	<a href="https://www.siliconsalon.info/salon3/presentations/"><img src="/assets/silicon-salon-3/presentations/cramium-presentation-2.jpg"></a>
	<a href="https://www.siliconsalon.info/salon3/presentations/"><img src="/assets/silicon-salon-3/presentations/cramium-presentation-3.jpg"></a>
</figure>

### Key Quotes

_Security:_ "The single-key scheme has become more risky."
{: .notice--info}

_Support:_ "Unfortunately there has not been much support from semiconductor
manufacturers for MPC and other schemes. We have identified this
problem, and Cramium was formed to help solve this challenge."
{: .notice--info}

_Speed:_ "Key generation here already takes several seconds or even
more than 10 seconds. This is one of the reasons why software-only
solutions are not good enough."
{: .notice--info}

_Goal:_
"We aim to provide a flexible and programmable computing platform, and
we want to take an open development approach."
{: .notice--info}

## Bunnie Studios Presentation

View [the video](https://www.youtube.com/watch?v=JMOWU6pFflw).

### Key Slides

<figure class="third">
	<a href="https://www.siliconsalon.info/salon3/presentations/"><img src="/assets/silicon-salon-3/presentations/bunnie-studios-presentation-1.jpg"></a>
	<a href="https://www.siliconsalon.info/salon3/presentations/"><img src="/assets/silicon-salon-3/presentations/bunnie-studios-presentation-2.jpg"></a>
	<a href="https://www.siliconsalon.info/salon3/presentations/"><img src="/assets/silicon-salon-3/presentations/bunnie-studios-presentation-3.jpg"></a>
</figure>

### Key Quotes

_Foundations:_
"If you can’t trust the transistors, then why bother with anything else?"
{: .notice--info}

_The Nth Turtle:_
"Let’s have open circuit boards, firmware, bootloader, kernel,
protocols, and applications. And also open chips, RTL, PDK, masks, and
chip fabs. The problem is that you can keep going down and down and
down until you get to the nth turtle."
{: .notice--info}

_Look Closer:_
"You can always walk around any security countermeasure by going one
level deeper and then trapping the upper security level in a state
where you are running a simulation and the world is not what it
appears."
{: .notice--info}

_Physical Hashes:_
"There is no 'hash function' and 'digital signature' for physical
hardware. At least not yet."
{: .notice--info}

_Tradeoffs:_
"Hardware security is a cost-benefit tradeoff at the end of the day,
like fatality rates in automobile accidents."
{: .notice--info}

##  Kavya Sreedhar Presentation

View [the video](https://www.youtube.com/watch?v=liMA-8zmu1E).

### Key Slides

<figure class="third">
	<a href="https://www.siliconsalon.info/salon3/presentations/"><img src="/assets/silicon-salon-3/presentations/sreedhar-presentation-1.jpg"></a>
	<a href="https://www.siliconsalon.info/salon3/presentations/"><img src="/assets/silicon-salon-3/presentations/sreedhar-presentation-2.jpg"></a>
	<a href="https://www.siliconsalon.info/salon3/presentations/"><img src="/assets/silicon-salon-3/presentations/sreedhar-presentation-3.jpg"></a>
</figure>

### Key Quotes

_New Needs:_
"Recently there has been a larger need for fast extended GCD
implementations."
{: .notice--info}

_Goal:_
"Our goal was to explore the broader design space across different
areas, like target platform, algorithm, and application requirements."
{: .notice--info}

## Additional Discussions

An hour's worth of additional discussion continued to iterate
through some of the topics brought up at Silicon Salon 3.

### Key Quotes: Hardware Challenges

"There's huge barriers to getting an algorithm into a chip."
{: .notice--info}

"We constantly struggle with a difference in mentality and constraints between software versus chip business."
{: .notice--info}

### Key Quotes: Hardware & Standards

"There's a lot of competing standards with MPC. ... [There's a] strong need for standardizing."
{: .notice--info}

"Without having standardization, the answer is probably to implement as many things as you can."
{: .notice--info}

### Key Quotes: Distributed Key Generation

"Distributed Key Generation is one of the best answers out there. Rather than worrying about your entropy, you just collect as much entropy as you can from as many parties as you can and that is your key generation."
{: .notice--info}

"We're kind of moving the secrets to a new place, and the damage they can do is reduced on an individual loss basis, but it's still a secret that requires some level of care."
{: .notice--info}

### Key Quotes: Collaboration

"We get to share a little bit about what we've been thinking about from the hardwaree perspective and importantly get to learn about what you all are thinking about from the cryptography application perspective, and that really informs what we're looking at next and how we can be helpful given our backgrounds.
{: .notice--info}

"This connection to being aware of what are the interesting problems and what's currently going on, that matters a lot!"
{: .notice--info}

"Thank you for listening to have what we have to save and sharing your knowledge with us."
{: .notice--info}

### Possible Future Discussions

Suggestions for future Silicon Salons include supply chain, standardization, and hardware open development.

## Participants

Thanks to our presenters and other participants!

* **Host:** [Blockchain Commons](https://www.blockchaincommons.com/)
* **Facilitators:** Christopher Allen, Bryan Bishop
* **Presenters:** [Bunnie Studios](https://www.bunniestudios.com/), [Cramium Labs](https://www.cramiumlabs.com/), [Kavya Sreedhar](https://profiles.stanford.edu/kavya-sreedhar)
* **Sustaining Sponsors:** [Bitmark](https://bitmark.com/), [Chia](https://www.chia.net/), [CrossBar](https://www.crossbar-inc.com/), [Foundation](https://foundationdevices.com/), [Proxy](https://www.proxy.com/), [Unchained Capital](https://unchained.com/)

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
