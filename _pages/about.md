---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am **Jinrong Zhang**, a PhD student at **Harbin Institute of Technology, Shenzhen**, supervised by [Prof. Jianlong Wu](https://jlwu1992.github.io). My research focuses on:

- Multimodal LLMs
- Multimodal Reasoning
- Open-World Object Detection and Segmentation
- Video Understanding and Temporal Analysis

I previously received my master's and bachelor's degrees from **Dalian University of Technology**. My work centers on robust visual perception and spatio-temporal reasoning, with publications in CVPR, AAAI, TNNLS, and ICME.

# 🔥 News
- *2026.03*: 🏆 Won **1st place** in both the **5th MOSE Challenge** and **5th MeViS-Text Challenge** at the CVPR Workshop PVUW Challenge.
- *2026*: 📄 First-author paper accepted by **CVPR 2026** on improving regional perception for multimodal large language models.
- *2025*: 📄 First-author paper accepted by **AAAI 2025** on open-set visual perception with image prompt paradigm.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><!-- TODO: Add paper image --></div></div>
<div class='paper-box-text' markdown="1">

[Breaking the Regional Perception Bottleneck of Multimodal Large Language Models via External Reasoning Framework](#)

**Jinrong Zhang** (First Author), CVPR (CCF-A), 2026

- Reveals pixel-level regional perception limitations in current MLLMs and proposes a multimodal MCTS-based reasoning framework that enables a 7B model to achieve performance comparable to 72B models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><!-- TODO: Add paper image --></div></div>
<div class='paper-box-text' markdown="1">

[Just a Few Glances: Open-Set Visual Perception with Image Prompt Paradigm](#)

**Jinrong Zhang** (First Author), AAAI (CCF-A), 2025

- Introduces visual prompts for open-world object detection and segmentation, reducing ambiguity in textual descriptions and improving performance and robustness.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><!-- TODO: Add paper image --></div></div>
<div class='paper-box-text' markdown="1">

[DTOS: Dynamic Time Object Sensing with Large Multimodal Model](#)

**Jinrong Zhang** (Co-First Author), CVPR (CCF-A), 2025

- Proposes a two-stage temporal-spatial refinement mechanism with task-specific quantitative tokens for precise spatio-temporal grounding in MLLMs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TNNLS 2025</div><!-- TODO: Add paper image --></div></div>
<div class='paper-box-text' markdown="1">

[End-to-End Streaming Video Temporal Action Segmentation With Reinforcement Learning](#)

**Jinrong Zhang** (First Author), TNNLS (IF = 8.9), 2025

- Pioneers a streaming-video paradigm for temporal action segmentation and introduces a reinforcement learning strategy to bridge the feature gap in online settings.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2025</div><!-- TODO: Add paper image --></div></div>
<div class='paper-box-text' markdown="1">

[Flexible Streaming Temporal Action Segmentation with Diffusion Models](#)

**Jinrong Zhang** (First Author), ICME (CCF-B), 2025

- Extends streaming temporal action segmentation to variable-length clips and adopts a diffusion architecture to improve temporal robustness.
</div>
</div>

# 🎖 Honors and Awards
- Outstanding Graduate, Dalian University of Technology
- International Underwater Robot Competition, Championship
- The 19th RoboMaster Robotics Competition, Second Prize
- China Robotics Competition (Underwater Robot Operations Project), Second Prize
- Chinese Collegiate Computing Competition, Second Prize

# 📖 Educations
- *2025.09 - 2029.06*, **Harbin Institute of Technology, Shenzhen**  
  PhD in Electronic Information, School of Computer Science and Technology (Supervisor: Prof. Jianlong Wu)
- *2022.09 - 2025.06*, **Dalian University of Technology**  
  Master in Control Science and Engineering, School of Control Science and Engineering
- *2018.09 - 2022.06*, **Dalian University of Technology**  
  Bachelor in Transportation Engineering, School of Transportation and Logistics

# 💻 Internships
- *2024.03 - 2024.09*, **Research Intern, Xiaomi**  
  Built an open-world detection and segmentation large-model solution for large die-casting defect detection at Xiaomi Automobile Factory; achieved +4.6% AP50 over SAM2 and over +30% gains on long-tail categories.
- *2026.02 - 2026.03*, **5th PVUW Challenge (CVPR Workshop)**  
  Won 1st place in both MOSE and MeViS-Text tracks with tracking-enhanced prompts and an MLLM-guided SAM3-agent pipeline.