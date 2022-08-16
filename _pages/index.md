---
permalink: /
title: "The Silicon Salon
layout: single
classes:
  - wide
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.25"
  overlay_image: /assets/images/silicon-salon-bare.jpg
salon1:
  - image_path: /assets/silicon-salon-1/presentations/silicon-salon-presentation.jpg
    alt: "Silicon Salon 1"
    title: "Silicon Salon 1"
    excerpt: 'The first Silicon Salon featured presentations by CrossBar, Proxy, Tropic Square, and Libre-SOC.'
    url: "/salon1/presentations/"
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

{% include feature_row id="salon1" type="left" %}




_Silicon background image courtesy of  [Vecteezy](https://www.vecteezy.com/vector-art/344822-printed-circuit-board-vector-illustration)_.
