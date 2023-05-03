---
permalink: /salon4/presentations/
title: "Silicon Salon IV: Presentations"
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
presentation_1:
  - image_path: /assets/silicon-salon-4/presentations/silicon-salon-presentation.jpg
    alt: "Silicon Salon Overview"
    title: "Silicon Salon Overview"
    excerpt: 'The Blockchain Commons presentation again led off the day.'
    url: ""
    btn_label: "Watch Intro"
    btn_class: "btn--info"
    url2: "/assets/silicon-salon-4/presentations/silicon-salon-presentation.pdf"
    btn_label2: "View Slides"
    btn_class2: "btn--success"
presentation_2:
  - image_path: /assets/silicon-salon-4/presentations/poelstra-presentation.jpg
    alt: "Andrew Poelstra Presentation"
    title: "Andrew Poelstra Presentation"
    excerpt: '**Anti-Exfil: Preventing Key Exfiltration Through Signature Nonce Data.** Secure nonce generation is a critical part of generating EC signatures, such as ECDSA or BIP-340 "Schnorr" signatures. If a hardware wallet fails to generate these nonces uniformly at random, then key leakage will occur. This talk introduces a protocol we term "anti-exfil", in which a hardware wallet and host computer engage in a 2-round interactive protocol to produce a signature."
    url: ""
    btn_label: "Watch Video"
    btn_class: "btn--info"
    url2: "/assets/silicon-salon-4/presentations/poelstra-presentation.pdf"
    btn_label2: "View Slides"
    btn_class2: "btn--success"
presentation_3:
  - image_path: /assets/silicon-salon-3/presentations/libresoc-presentation.jpg
    alt: "Luke Leighton & David Calderwood Presentation"
    title: "Luke Leighton & David Calderwood Presentation"
    excerpt: '**Scalar and Vector Draft Biginteger instructions for the Power ISA.** Most RISC ISAs are missing instructions that allow for easy chaining to create Vector results for biginteger operation. This presentation describes the need for 3-in 2-out instructions that greatly simplify biginteger operations as a key strategic requirement for semiconductor design.'
    url: ""
    btn_label: "Watch Video"
    btn_class: "btn--info"
    url2: "/assets/silicon-salon-4/presentations/libresoc-presentation.pdf"
    btn_label2: "View Slides"
    btn_class2: "btn--success"
presentation_4:
  - image_path: /assets/silicon-salon-3/presentations/cramium-presentation.jpg
    alt: "Cramium Labs Presentation"
    title: "Cramium Labs Presentation"
    excerpt: '**Pitfalls and Approaches to Open Source Security Semiconductor.** Open source is commonplace in software implementations of cryptographic functions. But it is not straightforward to extend this approach to security semiconductors. This talk describe some of the history of open source, explains Cramium&rsquo;s approach to navigating these problems, and provides at least some of the benefits of open source in the context of semiconductor design.'
    url: ""
    btn_label: "Watch Video"
    btn_class: "btn--info"
    url2: "/assets/silicon-salon-4/presentations/cramium-presentation.pdf"
    btn_label2: "View Slides"
    btn_class2: "btn--success"
---

{% include feature_row id="presentation_1" type="left" %}

{% include feature_row id="presentation_2" type="left" %}

{% include feature_row id="presentation_3" type="left" %}

{% include feature_row id="presentation_4" type="left" %}

