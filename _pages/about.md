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

I'm a Ph.D. student at [the Department of Computer Science and Technology, Tsinghua University](https://www.cs.tsinghua.edu.cn/) (清华大学计算机科学与技术系), advised by [Song-Hai Zhang](https://www.cs.tsinghua.edu.cn/info/1117/3538.htm) (张松海).
Before that, I achieved my bachelor's degree at [the School of Computer and Communication Engineering, University of Science and Technology Beijing](https://scce.ustb.edu.cn/) (北京科技大学计算机与通信工程学院).

My research interest focuses on <span style="color:red; font-weight: bold;">digital humans</span> and <span style="color:red; font-weight: bold;">computer vision</span>, including digital body/head avatar creation/editing, image/video generative models, and novel 3D representations. 

Now, I am in the fourth year of my five-year Ph.D. career and <span style="color:red; font-weight: bold;">will be graduating in June of 2025</span>. If you're looking for a digital human researcher, feel free to contact me (wangcong20@mails.tsinghua.edu.cn). BTW, the workplace is preferably in Beijing or somewhere around.


# 🔥 News
- *2023.08*: &nbsp;🎉 Neural Point-based Volumetric Avatars was accepted by **SIGRRAPH Asia 2023**!
- *2023.07*: &nbsp;🎉 LoLep was accepted by **ICCV 2023**!
- *2022.07*: &nbsp; I joined Tencent AI Lab as an intern.
- *2022.02*: &nbsp;🎉 MotionHint was accepted by **ICRA 2022**!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiV 2024</div><img src='images/mega_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MeGA: Hybrid Mesh-Gaussian Head Avatar for High-Fidelity Rendering and Head Editing](https://arxiv.org/abs/2404.19026)

**Cong Wang**, Di Kang, He-Yi Sun, Shen-Han Qian, Zi-Xuan Wang, Linchao Bao, Song-Hai Zhang

[**Project**](https://conallwang.github.io/MeGA_Pages/) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:9yKSN-GCB0IC'></span></strong>
- MeGA adopts more suitable representations to model different head components, achieving higher-quality renderings and naturally supporting various downstream applications (including hair alteration and texture editing).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH Asia 2023</div><img src='images/npva_teaser.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Neural Point-based Volumetric Avatar: Surface-guided Neural Points for Efficient and Photorealistic Volumetric Head Avatar](https://dl.acm.org/doi/10.1145/3610548.3618204)

**Cong Wang**, Di Kang, Yan-Pei Cao, Linchao Bao, Ying Shan, Song-Hai Zhang

[**Project**](https://conallwang.github.io/npva.github.io/) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:9yKSN-GCB0IC'></span></strong>
- NPVA employs neural points to achieve higher-quality renderings for challenging facial regions (e.g., mouth interior, eyes, and beard).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/lolep_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LoLep: Single-View View Synthesis with Locally-Learned Planes and Self-Attention Occlusion Inference](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_LoLep_Single-View_View_Synthesis_with_Locally-Learned_Planes_and_Self-Attention_Occlusion_ICCV_2023_paper.pdf)

**Cong Wang**, Yu-Ping Wang, Dinesh Manocha

[**Project**](None) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:2osOgNQ5qMEC'></span></strong>
- By regressing Locally-Learned Planes, LoLep is able to generate better novel views from one single RGB image. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2022</div><img src='images/motionhint_pipe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MotionHint: Self-Supervised Monocular Visual Odometry with Motion Constraints](https://dl.acm.org/doi/abs/10.1109/ICRA46639.2022.9812288)

**Cong Wang**, Yu-Ping Wang, Dinesh Manocha

[**Project**](https://github.com/conallwang/MotionHint) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:u5HHmVD_uO8C'></span></strong>
- MotionHint is able to be easily applied to existing open-sourced state-of-the-art SSM-VO systems to greatly improve the performance (reducing ATE by up to 28.73%).
</div>
</div>

- [ORBBuf: A robust buffering method for remote visual SLAM](https://dl.acm.org/doi/abs/10.1109/IROS51168.2021.9635950), Yu-Ping Wang, Zi-xin Zou, **Cong Wang**, et al. **IROS 2021**


# 🎖 Honors and Awards
- *2023.10* The Second Prize Scholarship (5,000RMB)
- *2023.09* Longhu Scholarship (5,000RMB)
- *2023.05* **2023 Tencent AI Lab Rhino-Bird Elite Talent**
- *2022.10* The Second Prize Scholarship (5,000RMB)
- *2022.09* Longhu Scholarship (5,000RMB)
- *2020.06* **Excellent Graduate of Beijing** (Top 5%)
- *2019.11* **National Scholarship** (8,000RMB, 1/446)
- *2019.04* the Mathematical Contest in Modeling, Meritorious Winner (Top 4%)
- *2018.11* **National Scholarship** (8,000RMB, 1/446)
- *2018.04* the Mathematical Contest in Modeling, Meritorious Winner (Top 4%)
- *2017.11* People's Special Scholarship (5,000RMB, 1/145)
- *2017.11* "Guan Zhi" Scholarship (10,000RMB, 1/446)

# 📖 Educations
- *2020.09 - 2024.04 (now)*, Ph.D. student, the Department of Computer Science and Technology, Tsinghua University, Beijing.
- *2016.09 - 2020.06*, Undergraduate, the School of Computer and Communication Engineering, University of Science and Technology Beijing, Beijing.

# 💬 Invited Talks
- *2023.12*, Oral Presentation for "Neural Point-based Volumetric Avatar: Surface-guided Neural Points for Efficient and Photorealistic Volumetric Head Avatar", SIGGRAPH Asia 2023, Sydney, NSW, Australia.
- *2023.11*, Show my paper, invited by [Journal of Image and Graphics](http://www.cjig.cn/jig/ch/index.aspx), [bilibili video](https://www.bilibili.com/video/BV1o64y177Ny/?spm_id_from=333.337.search-card.all.click&vd_source=b4eed9deaadbce01a5a20c7c9374a85e)
- *2022.07*, Show my paper, invited by [BKUNYUN](https://www.bkunyun.com/), [bilibili video](https://www.bilibili.com/video/BV1cB4y1C7Zw/?spm_id_from=333.337.search-card.all.click)
- *2022.05*, Oral Presentation for "MotionHint: Self-Supervised Monocular Visual Odometry with Motion Constraints", ICRA 2022, Philadelphia, PA, USA.

# 💻 Internships
- *2022.07 - 2024.07*, Tencent AI Lab, Beijing.
- *2024.07 - now*, AntGroup, Hangzhou.
