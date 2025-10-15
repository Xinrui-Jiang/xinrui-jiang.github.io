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

Hi there, I'm Xinrui "Ryan" Jiang, a master's student in EE at Stanford University. Prior to that, I received my B.Eng from Fudan University. During my undergraduate study, I was fortunate to be advised by Professor <a href='https://taco-group.github.io/index.html'>Zhengzhong Tu</a> at Texas A&M University and Professor <a href='https://nmr.mgh.harvard.edu/~berkin/index.html'>Berkin Bilgic</a> at Martinos Center for Biomedical Imaging/Harvard Medical School. 

My work focuses on generative AI, agentic AI, and low-level vision. I enjoy the process of formalizing complex real-world challenges into optimization problems, and deriving actionable solutions with data-driven computational methods.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/4kagent.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[4KAgent: Agentic Any Image to 4K Super-Resolution](https://arxiv.org/abs/2507.07105)

Yushen Zuo, Qi Zheng, Mingyang Wu, **Xinrui Jiang**, Renjie Li, Jian Wang, Yide Zhang, Gengchen Mai, Lihong V. Wang, James Zou, Xiaoyu Wang, Ming-Hsuan Yang, Zhengzhong Tu

[**Project Page**](https://4kagent.github.io/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We present 4KAgent, an agentic image super-resolution generalist designed to universally upscale any image to 4K resolution, regardless of input type, degradation level, or domain.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISMRM 2024</div><img src='images/nlcgnet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[NLCG-Net: A Model-Based Zero-Shot Learning Framework for Undersampled Quantitative MRI Reconstruction](https://arxiv.org/pdf/2401.12004)

**Xinrui Jiang**, Yohan Jun, Jaejin Cho, Mengze Gao, Xingwang Yong, Berkin Bilgic

[**Presentation**](https://www.youtube.com/watch?v=nFp378a-ygU) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We purposed NLCG-Net, a model-based and data-driven framework achieved via self-supervised learning, which incorporates nonlinear conjugate gradient optimization and Neural Network Regularization in a iterative manner and achieves zero-shot quantitative MRI reconstruction. T1, T2 mapping results on phantom and in-vivo data demonstrates NLCG-Net's superiority on estimation quality at high acceleration.
</div>
</div>

# 💻 Internships
- *2025.03 - 2025.08*, Machine Learning Engineer at [Microsoft](https://www.microsoft.com/en-us/aprd/aboutus/team-stca).
- *2025.03 - 2025.08*, Machine Learning at [TikTok/Bytedance](https://www.bytedance.com/en/).

# 🎖 Selected Awards
- *2023.09* Suiwei Scholarship (top 1%)
- *2022.09* National Scholarship (top 1%)

# 🌟 Fun
In my spare time, I enjoy running (~5km each time), making LEGO figure, and play with my cat Dafu (he is an American Shorthair)

<div style="display: flex; justify-content: space-between; align-items: flex-start; margin-top: 15px;">
<div style="flex-basis: 48%; text-align: center;">
<img src="{{ site.baseurl }}/images/fun_1.jpg" style="width: 100%; height: auto; border-radius: 5px;">
</div>

<div style="flex-basis: 48%; text-align: center;">
<img src="{{ site.baseurl }}/images/my_dafu.jpg" style="width: 100%; height: auto; border-radius: 5px;">
</div>
</div>
