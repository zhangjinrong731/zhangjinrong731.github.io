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


I am currently a Ph.D. student in Electronic Information at the School of Computer Science and Technology, Harbin Institute of Technology, Shenzhen , supervised by [Prof. Jianlong Wu](https://jlwu1992.github.io). Prior to this, I completed seven years of undergraduate and master's studies at Dalian University of Technology.

My current research interests focus on Multimodal Large Language Models, Multimodal Reasoning, Open World Object Detection and Segmentation, and Video Understanding & Temporal Analysis.

If you're interested in my research or have any research-related questions, please feel free to contact me via email at [zhangjinrong731@gmail.com](mailto:zhangjinrong731@gmail.com).

<span class='anchor' id='education'></span>

<span class='anchor' id='education'></span>
# 📖 Education
- *2025.09 - 2029.06*, **Harbin Institute of Technology, Shenzhen**  
  PhD in Electronic Information, School of Computer Science and Technology (Supervisor: Prof. Jianlong Wu)
- *2022.09 - 2025.06*, **Dalian University of Technology**  
  Master in Control Science and Engineering, School of Control Science and Engineering
- *2018.09 - 2022.06*, **Dalian University of Technology**  
  Bachelor in Transportation Engineering, School of Transportation and Logistics

<span class='anchor' id='experience'></span>

<span class='anchor' id='experience'></span>
# 💻 Internship Experience & Programs

- **Open World Object Detection & Segmentation:** Research Intern, Xiaomi, *2024.03 - 2024.09*
  - Developed an open-world detection and segmentation large model solution from scratch for the large die casting defect detection business at Xiaomi Automobile Factory. Outperformed SAM2 by achieving a 4.6% increase in AP50 on the proprietary validation set, with a significant >30% performance boost on long-tail categories.
  - Published a paper at AAAI based on the experimental research and findings conducted during the internship.

- **Complex Video Object Segmentation:** [CVPR Workshop, 5th PVUW Challenge](https://pvuw.github.io/), *2026.02 - 2026.03*
  - [**The 1st Winner for 5th MOSE Challenge:**](https://www.codabench.org/competitions/14016/#/results-tab) Proposed tracking-enhanced prompt strategy to improve SAM3's understanding capabilities for tiny and semantic-dominated objects, outperformed the 2nd place by 1.75% in J&F_new.
  - [**The 1st Winner for 5th MeViS-Text Challenge:**](https://www.codabench.org/competitions/14017/#/results-tab) Engineered an MLLM-guided SAM3-agent pipeline for iterative mask grounding and autonomous semantic refinement, outperformed the 2nd place by 7.91% in J&F.

<span class='anchor' id='publications'></span>

<span class='anchor' id='publications'></span>
# 📝 Publications 
\* Eauql contribution. # Corresponding author
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/rground.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Breaking the Regional Perception Bottleneck of Multimodal Large Language Models via External Reasoning Framework]()

**Jinrong Zhang**, Zhaoyang Xu, Xusheng He, Xinrui Li, Na Zheng, Jianlong Wu#
**First Author**, CVPR (CCF-A), 2026

- Revealed the limitations of current MLLMs in pixel-level regional perception and propose a multimodal MCTS-based reasoning framework to overcome this bottleneck, enabling a 7B model to achieve performance comparable to 72B.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/miground.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Just a Few Glances: Open-Set Visual Perception with Image Prompt Paradigm](https://ojs.aaai.org/index.php/AAAI/article/view/330)

**Jinrong Zhang**, Penghui Wang, Chunxiao Liu, Wei Liu, Dian Jin, Qiong Zhang#, Erli Meng#, Zhengnan Hu
**First Author**, AAAI (CCF-A), 2025

- Introduced a novel visual prompts for open-world object detection and segmentation, which bypasses the inherent ambiguity of textual descriptions and achieves enhanced performance and robustness.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/dtos.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DTOS: Dynamic Time Object Sensing with Large Multimodal Model](https://openaccess.thecvf.com/content/CVPR2025/papers/Tian_DTOS_Dynamic_Time_Object_Sensing_with_Large_Multimodal_Model_CVPR_2025_paper.pdf)

Jirui Tian\*, **Jinrong Zhang**\*, Shenglan Liu#, Luhao Xu, Zhixiong Huang, Gao Huang
**Co-First Author**, CVPR (CCF-A), 2025

- Designed DTOS for precise spatio-temporal grounding in MLLMs, utilizing a two-stage temporal-spatial refinement mechanism and task-specific quantitative tokens to accurately locate discontinuous targets while overcoming information loss caused by uniform sampling and natural language ambiguity.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TNNLS 2025</div><img src='images/svtas.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[End-to-End Streaming Video Temporal Action Segmentation With Reinforcement Learning](https://ieeexplore.ieee.org/abstract/document/10963907)

**JinRong Zhang**, WuJun Wen, ShengLan Liu, Gao Huang, YunHeng Li, QiFeng Li, Lin Feng#
**First Author**, TNNLS (IF = 8.9), 2025

- Pioneering a streaming video paradigm for temporal action segmentation unlocks ultra-long and online processing capabilities. Analyzing the intrinsic properties of streaming video and introducing a reinforcement learning paradigm successfully bridges the resulting feature gap.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2025</div><img src='images/fstas.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Flexible Streaming Temporal Action Segmentation with Diffusion Models](https://ieeexplore.ieee.org/document/11210093)

**Jinrong Zhang**, Wenjun Wen, Shenglan Liu, Sifan Zhang, Yuning Ding, Lin Feng#
**First Author**, ICME (CCF-B), 2025

- Extending to dynamic streaming video scenarios to evaluate intrinsic feature variations across variable-length clips, and deploying a diffusion model architecture that fundamentally shifts the task paradigm to yield temporal robustness.
</div>
</div>

<span class='anchor' id='achievements'></span>

<span class='anchor' id='achievements'></span>
# 🎖 Achievements
- Outstanding Graduate, Dalian University of Technology
- International Underwater Robot Competition, Championship
- The 19th RoboMaster Robotics Competition, Second Prize
- China Robotics Competition (Underwater Robot Operations Project), Second Prize
- Chinese Collegiate Computing Competition, Second Prize