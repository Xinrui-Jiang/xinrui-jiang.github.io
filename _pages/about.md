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

I am a fourth-year Biomedical Engineering undergraduate at Fudan University. During my undergraduate study, I was fortunate to be advised by Professor <a href='https://taco-group.github.io/index.html'>Zhengzhong Tu</a> at Texas A&M University and Professor <a href='https://nmr.mgh.harvard.edu/~berkin/index.html'>Berkin Bilgic</a> at Martinos Center for Biomedical Imaging/Harvard Medical School. Prior to that, I was also an undergraduate research student at Professor <a href='https://www.fudanroilab.com/'>Wenqiang Zhang</a>'s team.

My research interest lies in modeling real-world biomedical phenomena and solving corresponding challenges with computational methods, especially machine learning. Specifically, I distill specific problems into rigorous formulations, embedded with domain knowledge, and design tailored algorithms. To achieve this, my research orientation includes two intertwined branches: understanding frontier challenges in domains such as Imaging Neuroscience and Inverse Problems; studying state-of-the-art methodology in self-supervised learning, generative AI, and numerical optimization.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISMRM 2024</div><img src='images/pj.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[NLCG-Net: A Model-Based Zero-Shot Learning Framework for Undersampled Quantitative MRI Reconstruction](https://arxiv.org/pdf/2401.12004)

**Xinrui Jiang**, Yohan Jun, Jaejin Cho, Mengze Gao, Xingwang Yong, Berkin Bilgic

[**Presentation**](https://www.youtube.com/watch?v=nFp378a-ygU) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We purposed NLCG-Net, a model-based and data-driven framework achieved via self-supervised learning, which incorporates nonlinear conjugate gradient optimization and Neural Network Regularization in a iterative manner and achieves zero-shot quantitative MRI reconstruction. T1, T2 mapping results on phantom and in-vivo data demonstrates NLCG-Net's superiority on estimation quality at high acceleration.
</div>
</div>

# 🎖 Honors and Awards
- *2023.09* SuiWei Scholarship named by Weiqi Wang, Academician, Chinese Academy of Engineering (the first prize, top 1%).
- *2022.12* The First Prize of the 14th Mathematics Competition of Chinese College Students in Shanghai
- *2022.09* National Scholarship of Fudan University (top 1% at Fudan University).
- *2021.12* The First Prize of the 13th Mathematics Competition of Chinese College Students in Shanghai


# 📖 Educations
- *2021.09 - 2025.06 (now)*, Fudan University, GPA: 3.81/4.00 (ranking 2/272 among college)
- *2023.09 - 2023.12*, University of Toronto, GPA: 3.9/4.0
- *2022.06 - 2022.8*, Harvard University Summer School, GPA: 4.0/4.0 (graduate credit) 

# 💻 Internships
- *2024.01 - 2024.04*, Machine Learning Engineer, [Tiktok (Bytedance)](https://www.bytedance.com/en/), China.
