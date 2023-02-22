---
permalink: /salon2/intro-transcript/
title: "Transcript of Silicon Salon 2 Introduction"
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

Thank you everyone for joining us this morning. This is our second Silicon Salon, this time on the topic of supply chain security, firmware and boot and those associated topics. This is a collaborative session. If you want to view the slides directly, there is a URL for them which I will put in the chatroom. There also is collaborative notes.

What is Blockchain Commons? Our goal is to bring together blockchain, web3, and web5 and other stakeholders together to collaboratively develop interoperable infrastructure. We design decentralized solutions where everyone wins. To do that, we have to act as a neutral not-for-profit that enables people to control their digital destiny. I am Christopher Allen and architect of Blockchain Commons and coauthor of the DID standard, organizer of Rebooting Web of Trust, and back in the day co-author of the TLS 1.0 standard.

What is Silicon Salon? Our goal with these is to facilitate wallet developers and semiconductor chip manufacturers to identify problems and assess needs. That's very much what we're doing in this salon. We want to take the results from these group salons and learn to collaboratively engineer interoperable specifications. There's silicon logic, cryptographic logic, APIs, and then all the topics today. There's a lot of opportunities for cooperation here. How do we create the right incentives for cooperation? We want to evangelize these solutions to the larger ecosystem, and we want to support our partners with reference code and test suites so that they can develop their own versions of all of these different tools.

Who are you? We have some semiconductor chip designers, we have Bunnie Studios, Tropic Square, wallet hardware manufacturers like Proxy and Foundation Devices, the team behind Validated Lightning Signer, and others from Blockchain Commons involvement, and we have other people in the ecosystem that play other parts like Bitmark with NFT, Unchained Capital offering some collaborative custody, Blockchain Bird promoting blockchain self-sovereignty, and then the Human Rights Foundation. Among us, we have some cryptographers, protocol designers, and engineers. These are the people participating in these types of events.

Our last event was focused on the high-level of requirements for secure hardware, pain points and architectures. We had 5 presentations. Out of all the different discussions, we decided the most important thing to start with was boot, firmware and supply chain, which we will be exploring today. How do we boot securely? How do we ensure the firmware is secure? How can firmware be updated? How do we ensure the supply chain has not been compromised?

The process today is starting with multiple presentations, probably about an hour and a half. We will take a brief standing break and then we will go through a Q&A on a lot of these different topics, brainstorm with each other, and reserve the last 15 minutes for "who are the next steps and who else do we want to be involved in the next Silicon Salon that we could invite who otherwise might not attend". I hope you can stay for the whole meeting.

Chatham house rules: you are free to use this information, but not attributing identities to quotes. Although we are recording, we will not be sharing the recording of the Q&A. We are only recording to be able to provide the presentations and anonymized summaries. If we take a quote even without your name, and you don't want it, we will be glad to remove that from the final summary.

We have 5 presentations today beginning with Bunnie Studios, then Cramium, Proxy, Foundation Devices, and concludingv with Validated Lightning Signing. We are starting with level0 or layer -1, the silicon layer, and then layer zero, and Validated Lightning Signer is dealing with requirements on layer 2 so it's good that we have a good mix on the hardware requirements today. 
