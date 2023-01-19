---
permalink: /
title: "The Silicon Salon"
subtitle: "Semiconductor Solutions for Cryptography"
layout: single
classes:
  - wide
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.25"
  overlay_image: /assets/images/silicon-salon-bare.jpg
salon2:
  - image_path: /assets/silicon-salon-3/presentations/silicon-salon-presentation.jpg
    alt: "Silicon Salon 3"
    title: "Silicon Salon 3"
    excerpt: '**January 18, 2023.** Our third salon discussed new silicon-logic-based cryptographic functionality & leveraging opportunities for semiconductor acceleration, such as Multi-Party Computation (MPC) and ZK-proofs.'
    url: "/salon3/"
    btn_label: "Overview"
    btn_class: "btn--success"
    url2: "/salon3/presentations/"
    btn_label2: "Presentations"
    btn_class2: "btn--info"
salon2:
  - image_path: /assets/silicon-salon-2/presentations/silicon-salon-presentation.jpg
    alt: "Silicon Salon 2"
    title: "Silicon Salon 2"
    excerpt: '**September 14, 2022.** Our second salon discussed bootloaders, firmware, and supply chains.'
    url: "/salon2/"
    btn_label: "Overview"
    btn_class: "btn--success"
    url2: "/salon2/presentations/"
    btn_label2: "Presentations"
    btn_class2: "btn--info"
salon1:
  - image_path: /assets/silicon-salon-1/presentations/silicon-salon-presentation.jpg
    alt: "Silicon Salon 1"
    title: "Silicon Salon 1"
    excerpt: '**June 1, 2022.** The first Silicon Salon featured presentations by CrossBar, Proxy, Tropic Square, and Libre-SOC.'
    url: "/salon1/"
    btn_label: "Overview"
    btn_class: "btn--success"
    url2: "/salon1/presentations/"
    btn_label2: "Presentations"
    btn_class2: "btn--info"
---

{% capture notice-1 %}
{% include nextevent.md %}
{% endcapture%}

<div class="notice--success">{{ notice-1 | markdownify }}</div>

***What is the Silicon Salon?*** Currently, there are no semiconductors designed specifically for crypto-wallets, forcing wallet developers to cobble together solutions from what exists. Fortunately, that’s about to change, thanks to semiconductor manufacturers such as CrossBar and Tropic Square, who are seeking to directly address the cryptocurrency, digital identity & assets markets. 

The object of the Silicon Salons is to bring together these two groups: wallet developers and semiconductor manufacturers. By working together, we can ensure that the first generation of cryptographic semiconductors meets everyone's needs, advancing the entire cryptography industry.

---

{% include feature_row id="salon3" type="left" %}

{% include feature_row id="salon2" type="left" %}

{% include feature_row id="salon1" type="left" %}




_Silicon background image courtesy of  [Vecteezy](https://www.vecteezy.com/vector-art/344822-printed-circuit-board-vector-illustration)_.
