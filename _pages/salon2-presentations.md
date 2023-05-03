---
permalink: /salon2/presentations/
title: "Silicon Salon II: Presentations"
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
presentation_1:
  - image_path: /assets/silicon-salon-2/presentations/silicon-salon-presentation.jpg
    alt: "Silicon Salon Overview"
    title: "Silicon Salon Overview"
    excerpt: 'The Blockchain Commons presentation led off the day and our three major topics.'
    url: "https://www.youtube.com/watch?v=9j7e0XnTy9o"
    btn_label: "Watch Intro"
    btn_class: "btn--info"
    url2: "/assets/silicon-salon-2/presentations/silicon-salon-presentation.pdf"
    btn_label2: "View Slides"
    btn_class2: "btn--success"
    url3: "https://www.siliconsalon.info/salon2/intro-transcript/"
    btn_label3: "Read Transcript"
    btn_class3: "btn--success"
presentation_2:
  - image_path: /assets/silicon-salon-2/presentations/bunnie-studios-presentation.png
    alt: "Bunnie Studios Presentation"
    title: "Bunnie Studios Presentation"
    excerpt: '**Precursor.** Precursor is an open-source platform for developing secure mobile apps. Based on an FPGA, it is used to battle-test real-world scenarios prior to a planned SoC tape-out. Includes a tour of the secure boot and key self-provisioning.'
    url: "https://www.youtube.com/watch?v=IlM4mFv2nM4"
    btn_label: "Watch Video"
    btn_class: "btn--info"
    url2: "/assets/silicon-salon-2/presentations/bunnie-studios-presentation.pdf"
    btn_label2: "View Slides"
    btn_class2: "btn--success"
    url3: "https://diyhpl.us/wiki/transcripts/silicon-salon/precursor/"
    btn_label3: "Read Transcript"
    btn_class3: "btn--success"
presentation_3:
  - image_path: /assets/silicon-salon-2/presentations/cramium-presentation.jpg
    alt: "Cramium Presentation"
    title: "Cramium Presentation"
    excerpt: '**Bootloading.** Cramium Labs is a division of Crossbar Inc., focused on security system-on-a-chip products incorporating RRAM. Their presentation asks: What should the Controller Manufacturer bootloader do? Should it only open the communication ports or should it open the comm channels, perform self-test, and perform all crypto functions, or something in-between?'
    url: "https://www.youtube.com/watch?v=Np7Mw-jf0WY"
    btn_label: "Watch Video"
    btn_class: "btn--info"
    url2: "/assets/silicon-salon-2/presentations/cramium-presentation.pdf"
    btn_label2: "View Slides"
    btn_class2: "btn--success"
    url3: "https://diyhpl.us/wiki/transcripts/silicon-salon/cramium-bootloader/"
    btn_label3: "Read Transcript"
    btn_class3: "btn--success"
presentation_4:
  - image_path: /assets/silicon-salon-2/presentations/foundation-presentation.jpg
    alt: "Foundation Presentation"
    title: "Foundation Presentation"
    excerpt: '**How Passport Uses Silicon Features to Secure Your Bitcoin.** Passport is a modern Bitcoin hardware wallet that combines ease of use with strong security. This talk covers some of the key features that are built into Passport&rsquo;s bootloader, firmware update process, and supply-chain activation process. In particular, it covers how those features use the Secure Element and MCU to provide security.'
    url: "https://www.youtube.com/watch?v=ZCZ_dwui-X0"
    btn_label: "Watch Video"
    btn_class: "btn--info"
    url2: "/assets/silicon-salon-2/presentations/foundation-presentation.pdf"
    btn_label2: "View Slides"
    btn_class2: "btn--success"
    url3: "https://diyhpl.us/wiki/transcripts/silicon-salon/foundation-devices/"
    btn_label3: "Read Transcript"
    btn_class3: "btn--success"    
presentation_5:
  - image_path: /assets/silicon-salon-2/presentations/proxy-presentation.jpg
    alt: "Proxy Presentation"
    title: "Proxy Presentation"
    excerpt: '**Hardware Security.** Proxy makes a web3 identity wallet and a companion wearable hardware crypto-wallet. Their focus is ease of use by a non-technical audience, coupled with strong and opinionated default security. This talk is about steps they are taking in assuring the security and integrity of their hardware.'
    url: "https://www.youtube.com/watch?v=MV-Q9PVQZ-o"
    btn_label: "Watch Video"
    btn_class: "btn--info"
    url2: "/assets/silicon-salon-2/presentations/proxy-presentation.pdf"
    btn_label2: "View Slides"
    btn_class2: "btn--success"
    url3: "https://diyhpl.us/wiki/transcripts/silicon-salon/proxy-bootloader/"
    btn_label3: "Read Transcript"
    btn_class3: "btn--success"    
presentation_6:
  - image_path: /assets/silicon-salon-2/presentations/vls-presentation.jpg
    alt: "VLS Presentation"
    title: "VLS Presentation"
    excerpt: '**Validating Lightning Signer**. The VLS project builds software that enables the private-key material and sensitive signing operations for a Lightning node to be stored and executed in a separate secure environment. The VLS project is open-source and is written in Rust. There is interest in integrating the VLS software with secure hardware execution environments.'
    url: "https://www.youtube.com/watch?v=zY8I-ec9rHY"
    btn_label: "Watch Video"
    btn_class: "btn--info"
    url2: "/assets/silicon-salon-2/presentations/vls-presentation.pdf"
    btn_label2: "View Slides"
    btn_class2: "btn--success"
    url3: "https://diyhpl.us/wiki/transcripts/silicon-salon/validating-lightning-signer/"
    btn_label3: "Read Transcript"
    btn_class3: "btn--success"
---

{% include feature_row id="presentation_1" type="left" %}

{% include feature_row id="presentation_2" type="left" %}

{% include feature_row id="presentation_3" type="left" %}

{% include feature_row id="presentation_4" type="left" %}

{% include feature_row id="presentation_5" type="left" %}

{% include feature_row id="presentation_6" type="left" %}
