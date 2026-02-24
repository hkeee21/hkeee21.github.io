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

I'm Ke Hong (洪可), a Ph.D. candidate at [NICS-EFC Lab](https://nicsefc.ee.tsinghua.edu.cn/), supervised by Prof. Yu Wang. My research interest includes machine learning systems (MLSys) and high-performance computing on GPUs. Recently, I have been engaged in optimizing the serving systems for large language models (LLMs) and visual generative models. 

I have published about 20 papers, including 6 as the first/co-first author in top conferences such as MLSys, EuroSys, and NeurIPS, with a citation of <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. I aim to do research that is interesting and useful.

If you are interested in any of my works or potential collaborations, feel free to reach out—I’d be happy to connect!

# 🔥 News
- *2026.02*: &nbsp;🧨 Happy Chinese New Year!
- *2026.01*: &nbsp;🎉 Paper *db*-SP is accepted by MLSys'26. 

# 📓 Downloading CV

[**Chinese version**](https://nicsefc.ee.tsinghua.edu.cn/nics_file/pdf/fcf88c87-b7a6-4b09-a74a-055d89bf5d8d.pdf) | English version

# 📖 Educations
- *2024.08 - now*, Ph.D. candidate, Department of Electronic Engineering, Tsinghua University. 
- *2021.08 - 2024.06*, Master, Shenzhen Graduate School, Tsinghua University. 
- *2017.08 - 2021.06*, Bachelor, Department of Electronic Engineering, Tsinghua University.

# 📝 Publications 

(* indicates equal contribution, † indicates corresponding authors.)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MLSys 2026 (accepted)</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*db*-SP: Accelerating Sparse Attention for Visual Generative Models with Dual-balanced Sequence Parallelism

Siqi Chen *, **Ke Hong** *, Tianchen Zhao, Ruiqi Xie, Zhenhua Zhu, Xudong Zhang, Yu Wang †

[**Paper**](https://arxiv.org/pdf/2511.23113) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> | 
[**Code**](https://github.com/thu-nics/db-SP) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EuroSys 2026 (accepted)</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Efficient and Adaptable Overlapping for Computation
and Communication via Signaling and Reordering

**Ke Hong**, Xiuhong Li †, Minxu Liu, Qiuli Mao, Tianqi Wu, Zixiao Huang, Lufang Chen, Zhong Wang, Yichong Zhang, Zhenhua Zhu, Guohao Dai †, Yu Wang †

[**Paper**](https://arxiv.org/pdf/2504.19519) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> |
[**Code**](https://github.com/infinigence/FlashOverlap) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

PAROAttention: Pattern-Aware ReOrdering for Efficient Sparse and Quantized Attention in Visual Generation Models

Tianchen Zhao *, **Ke Hong** *, Xinhao Yang *, Xuefeng Xiao, Huixia Li, Feng Ling, Ruiqi Xie, Siqi Chen, Hongyu Zhu, Yichong Zhang, Yu Wang †

[**Paper**](https://openreview.net/pdf?id=UPELg2oUo3) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MLSys 2025</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

SOLA: Optimizing SLO Attainment for Large Language Model Serving with State-Aware Scheduling

**Ke Hong**, Xiuhong Li †, Lufang Chen, Qiuli Mao, Xuefei Ning, Guohao Dai †, Shengen Yan, Yun Liang, Yu Wang †

[**Paper**](https://proceedings.mlsys.org/paper_files/paper/2025/file/bc82dbfbfa43232be85b8d9838f49c3e-Paper-Conference.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MLSys 2024</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

FlashDecoding++: Faster Large Language Model Inference with Asynchronization, Flat GEMM Optimization, and Heuristics

**Ke Hong** *, Guohao Dai *†, Jiaming Xu *, Qiuli Mao, Xiuhong Li, Jun Liu, Kangdi Chen, Yuhan Dong, Yu Wang †

[**Hugging Face Daily Paper #1**](https://huggingface.co/papers/2311.01282) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> | 
[**Paper**](https://proceedings.mlsys.org/paper_files/paper/2024/file/5321b1dabcd2be188d796c21b733e8c7-Paper-Conference.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> |
[**Demo**](https://github.com/hkeee21/FlashDecodingPlusAE) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MLSys 2023</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Exploiting Hardware Utilization and Adaptive Dataflow for Sparse Convolution in 3D Point Clouds

**Ke Hong** *, Zhongming Yu *, Guohao Dai †, Xinhao Yang, Yaoxiu Lian, Zehao Liu, Ningyi Xu, Yuhan Dong, Yu Wang †

[**Paper**](https://proceedings.mlsys.org/paper_files/paper/2023/file/8e3e27d07b3f663b7f85c819b9692163-Paper-mlsys2023.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> |
[**Code**](https://github.com/hkeee21/PCEngine) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>


# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.

# 🖊️ Teaching

# 🏐 Hobbies
