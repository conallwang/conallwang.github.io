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

I am currently a scientific researcher in the World Model Team at Tencent Hunyuan (腾讯混元), focusing on Video World Models. Prior to this, I worked in the Applied Model Center at Tencent Hunyuan, where my research centered on identity-consistent video generation models.

I received my Ph.D. degree from [the Department of Computer Science and Technology, Tsinghua University](https://www.cs.tsinghua.edu.cn/) (清华大学计算机科学与技术系), advised by [Prof. Song-Hai Zhang](https://www.cs.tsinghua.edu.cn/info/1117/3538.htm) (张松海) and [Prof. Yu-Ping Wang](https://scholar.google.com/citations?hl=en&user=QqdDO64AAAAJ)(王瑀屏). The lab's name is CSCG, created by [Prof. Shimin Hu](https://scholar.google.com/citations?user=LDb4tb0AAAAJ&hl=en)(胡事民). During my Ph.D., I had three wonderful internship experiences: I interned at Tencent AI Lab for two years working on 3D digital human representation and animation with [Di Kang](https://scholar.google.com/citations?user=2ztThPwAAAAJ&hl=en)(康頔) and [Linchao Bao](https://linchaobao.github.io/)（暴林超）; I spent one year at Interaction Intelligence Lab, Ant Research, exploring 3D digital human generation and animation with [Xuan Wang](https://xuanwangvc.github.io/)(王璇); and I also worked as an Ali-Star (阿里星) intern at Taotian Group, researching digital human expression animation. Before my Ph.D., I achieved my bachelor's degree at [the School of Computer and Communication Engineering, University of Science and Technology Beijing](https://scce.ustb.edu.cn/) (北京科技大学计算机与通信工程学院).

My current research interest focuses on <span style="color:red; font-weight: bold;">Video World Models, Multimodal Generation, and Digital Human AI</span>.

# 🔥 News
- *2026.06*: &nbsp;🎉 **HarmoView** was released on arXiv!
- *2026.05*: &nbsp;🎉 **SpongeBob** was released on arXiv!
- *2025.07*: &nbsp; I joined **Tencent Hunyuan** as a scientific researcher.
- *2025.07*: &nbsp;🎉 2 papers is accepted by **ICCV 2025**!
- *2025.03*: &nbsp;🎉 **MeGA** was accepted by **CVPR 2025**!
- *2024.07*: &nbsp; I joined **AntGroup** as an intern.
- *2023.08*: &nbsp;🎉 **Neural Point-based Volumetric Avatars** was accepted by **SIGRRAPH Asia 2023**!
- *2023.07*: &nbsp;🎉 **LoLep** was accepted by **ICCV 2023**!
- *2022.07*: &nbsp; I joined **Tencent AI Lab** as an intern.
- *2022.02*: &nbsp;🎉 **MotionHint** was accepted by **ICRA 2022**!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/harmoview_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HarmoView: Harmonizing Multi-View Constraints for Identity-Consistent Video Generation](https://arxiv.org/abs/2606.10839)

**Cong Wang**, Zhentao Yu, Hongmei Wang, Weicong Liang, Zixiang Zhou, Zilin Yang, Jiarong Ou, Rui Chen, Yezhou Liu, Shiyu An, Yue Lu, Yuan Zhou, Qinglin Lu

[**Project**](https://conallwang.github.io/HarmoView_Pages/) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:9yKSN-GCB0IC'></span></strong>
- We propose **HarmoView**, a robust framework for **identity-consistent video generation** that effectively integrates **multi-view cues** via three architectural refinements—**Multi-level Feature Injection**, **learnable proxy tokens**, and **Jump-RoPE**—together with a **Progressive View Curriculum** to enable stable multi-view training on top of a pre-trained T2V model.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/spongebob_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SpongeBob: Sync-Aware Harmonious Audio-Visual Generative Editing](https://arxiv.org/abs/2605.25193)

Sen Liang, **Cong Wang**, Fengbin Guan, Zhentao Yu, Yiting Lu, Yuanzhi Wang, Yuan Zhou, Xin Li, Zhibo Chen

[**Project**](https://hy-spongebob.github.io/) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:9yKSN-GCB0IC'></span></strong>
- SpongeBob is **the first end-to-end audio-visual joint editing framework** built on a dual-stream DiT, featuring a **Sync-Aware Editing Mechanism** for temporal/spatial alignment and a **Context-Aware Module** for consistency with preserved content, delivering harmonious video-audio co-editing.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/pipeline.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SVG-Head: Hybrid Surface-Volumetric Gaussians for High-Fidelity Head Reconstruction and Real-Time Editing](https://arxiv.org/pdf/2508.09597)

He-Yi Sun, **Cong Wang**, Tian-Xing Xu, Jingwei Huang, Di Kang, Chunchao Guo, Song-Hai Zhang

[**Project**](https://heyy-sun.github.io/SVG-Head/) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:9yKSN-GCB0IC'></span></strong>
- By proposing **surf-GS for modeling global appearance as a texture image** and **vol-GS for high-fidelity rendering of non-Lambertian regions**, SVG-Head supports not only high-quality renderings, but also real-time, fine-grained texture editing.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/finegrained_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fine-Grained 3D Gaussian Head Avatars Modeling from Static Captures via Joint Reconstruction and Registration](https://openaccess.thecvf.com/content/ICCV2025/papers/Sun_Fine-Grained_3D_Gaussian_Head_Avatars_Modeling_from_Static_Captures_via_ICCV_2025_paper.pdf)

Yuan Sun, Xuan Wang, **Cong Wang**, WeiLi Zhang, Yanbo Fan, Yu Guo, Fei Wang

[**Paper**](https://openaccess.thecvf.com/content/ICCV2025/html/Sun_Fine-Grained_3D_Gaussian_Head_Avatars_Modeling_from_Static_Captures_via_ICCV_2025_paper.html) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:9yKSN-GCB0IC'></span></strong>
- We formulate 3D Gaussian head avatar modeling from static captures as a **joint reconstruction and registration** problem, optimizing a **prior-based** and a **prior-free** set of Gaussians and binding them via **non-rigid ICP**, producing fine-grained, animatable avatars at high resolutions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/mega_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MeGA: Hybrid Mesh-Gaussian Head Avatar for High-Fidelity Rendering and Head Editing](https://arxiv.org/abs/2404.19026)

**Cong Wang**, Di Kang, He-Yi Sun, Shen-Han Qian, Zi-Xuan Wang, Linchao Bao, Song-Hai Zhang

[**Project**](https://conallwang.github.io/MeGA_Pages/) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:9yKSN-GCB0IC'></span></strong>
- By proposing the use of **more appropriate representations for different parts of the human head** and the corresponding **hybrid rendering methods**, we produce **high-quality** 3D human head avatar, and for the first time, **support human head editing** (i.e., texture editing and hair alteration).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH Asia 2023</div><img src='images/npva_teaser.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Neural Point-based Volumetric Avatar: Surface-guided Neural Points for Efficient and Photorealistic Volumetric Head Avatar](https://dl.acm.org/doi/10.1145/3610548.3618204)

**Cong Wang**, Di Kang, Yan-Pei Cao, Linchao Bao, Ying Shan, Song-Hai Zhang

[**Project**](https://conallwang.github.io/npva.github.io/) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:9yKSN-GCB0IC'></span></strong>
- We propose a new **surface-guided neural point representation** and the corresponding **rendering acceleration method** to greatly improve the rendering quality of **eyes and mouth interiors** in 3D digital human head modeling.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/lolep_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LoLep: Single-View View Synthesis with Locally-Learned Planes and Self-Attention Occlusion Inference](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_LoLep_Single-View_View_Synthesis_with_Locally-Learned_Planes_and_Self-Attention_Occlusion_ICCV_2023_paper.pdf)

**Cong Wang**, Yu-Ping Wang, Dinesh Manocha

[**Project**](None) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:2osOgNQ5qMEC'></span></strong>
- We propose to use **an NN Sampler** for **more certain and reasonable MPI plane locations** and introduce a reprojection loss to facilitate sampler learning. Additionally, we propose **the block self-attention mechanism** to enhance the network's inference ability for the occluded regions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2022</div><img src='images/motionhint_pipe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MotionHint: Self-Supervised Monocular Visual Odometry with Motion Constraints](https://dl.acm.org/doi/abs/10.1109/ICRA46639.2022.9812288)

**Cong Wang**, Yu-Ping Wang, Dinesh Manocha

[**Project**](https://github.com/conallwang/MotionHint) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:u5HHmVD_uO8C'></span></strong>
- We introduce **the motion prior** of camera carriers (mainly unmanned vehicles) via **a pre-trained PPNet**, so that the predicted camera poses can be corrected according to the motion prior, yielding the state of art results.
</div>
</div>

- [ORBBuf: A robust buffering method for remote visual SLAM](https://dl.acm.org/doi/abs/10.1109/IROS51168.2021.9635950), Yu-Ping Wang, Zi-xin Zou, **Cong Wang**, et al. **IROS 2021**


# 🎖 Honors and Awards
- *2024.11* **Huawei Scholarship** (¥20,000) 
- *2024.07* **2023 Tencent AI Lab Rhino-Bird Elite Talent, Excellence Award**
- *2023.10* The Second Prize Scholarship (¥5,000)
- *2023.09* Longhu Scholarship (¥5,000)
- *2023.05* **2023 Tencent AI Lab Rhino-Bird Elite Talent**
- *2022.10* The Second Prize Scholarship (¥5,000)
- *2022.09* Longhu Scholarship (¥5,000)
- *2020.06* **Excellent Graduate of Beijing** (Top 5%)
- *2019.11* **National Scholarship** (¥8,000, 1/446)
- *2019.04* the Mathematical Contest in Modeling, Meritorious Winner (Top 4%)
- *2018.11* **National Scholarship** (¥8,000, 1/446)
- *2018.04* the Mathematical Contest in Modeling, Meritorious Winner (Top 4%)
- *2017.11* People's Special Scholarship (¥5,000, 1/145)
- *2017.11* "Guan Zhi" Scholarship (¥10,000, 1/446)

# 📖 Educations
- *2020.09 - 2025.06*, Ph.D. student, the Department of Computer Science and Technology, Tsinghua University, Beijing.
- *2016.09 - 2020.06*, Undergraduate, the School of Computer and Communication Engineering, University of Science and Technology Beijing, Beijing.

# 💬 Invited Talks
- *2023.12*, Oral Presentation for "Neural Point-based Volumetric Avatar: Surface-guided Neural Points for Efficient and Photorealistic Volumetric Head Avatar", SIGGRAPH Asia 2023, Sydney, NSW, Australia.
- *2023.11*, Show my paper, invited by [Journal of Image and Graphics](http://www.cjig.cn/jig/ch/index.aspx), [bilibili video](https://www.bilibili.com/video/BV1o64y177Ny/?spm_id_from=333.337.search-card.all.click&vd_source=b4eed9deaadbce01a5a20c7c9374a85e)
- *2022.07*, Show my paper, invited by [BKUNYUN](https://www.bkunyun.com/), [bilibili video](https://www.bilibili.com/video/BV1cB4y1C7Zw/?spm_id_from=333.337.search-card.all.click)
- *2022.05*, Oral Presentation for "MotionHint: Self-Supervised Monocular Visual Odometry with Motion Constraints", ICRA 2022, Philadelphia, PA, USA.

# 💻 Work
- *2025.07 - now*,     Tencent Hunyuan, Beijing.
- *2025.05 - 2025.07*, Taotian Group, Hangzhou.
- *2024.07 - 2025.05*, AntGroup, Hangzhou.
- *2022.07 - 2024.07*, Tencent AI Lab, Beijing.

