---
permalink: /
layout: jon
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

I am a Ph.D. student at the Hong Kong University of Science and Technology (HKUST), supervised by Prof. [Jun Zhang](https://eejzhang.people.ust.hk/home.html). I received my B.E. degree from Beihang University. Currently, I am interested in multimodal reinforcement learning (*e.g.*, VLMs and diffusion models). Moreover, I focus on efficient training and inference for vision and language generative models.


<!-- <span class='anchor' id='-news'></span> -->
<!-- # News
<div class="news-list">
  <ul>
    <li><span class="news-date">2025.11</span><span>Our SlimInfer and LLMC+ are accepted to AAAI.</span></li>
    <li><span class="news-date">2025.06</span><span>Our Temporal Feature Matters is accepted to TPAMI.</span></li>
    <li><span class="news-date">2025.05</span><span>Our HarmoniCa is accepted to ICML.</span></li>
    <li><span class="news-date">2024.10</span><span>Our LLMC is accepted to EMNLP Industry Track.</span></li>
    <li><span class="news-date">2024.07</span><span>Our PTSBench is accepted to ACM MM.</span></li>
    <li><span class="news-date">2024.02</span><span>Our TFMQ-DM is accepted to CVPR as a Highlight Poster (Top 2.8%).</span></li>
  </ul>
</div> -->

<span class='anchor' id='-news'></span>
# News

<div class="news-box" markdown="1">
- *2026.01*: &nbsp;🎉🎉 Our QVGen is accepted to ICLR.
- *2025.11*: &nbsp;🎉🎉 Our SlimInfer and LLMC+ are accepted to AAAI.
- *2025.06*: &nbsp;🎉🎉 Our Temporal Feature Matters is accepted to TPAMI.
- *2025.05*: &nbsp;🎉🎉 Our HarmoniCa is accepted to ICML.
- *2024.10*: &nbsp;🎉🎉 Our LLMC is accepted to EMNLP Industry Track.
- *2024.07*: &nbsp;🎉🎉 Our PTSBench is accepted to ACM MM.
- *2024.02*: &nbsp;🎉🎉 Our TFMQ-DM is accepted to CVPR as a Highlight Poster (Top $2.8\%$).
</div>

<span class='anchor' id='-publications'></span>
# Selected Papers
<span style="color:#6a737d">Includes preprints; * indicates equal contribution, 📧 indicates corresponding author</span>

<div class="pub-grid-2">

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/modes.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MoDES: Accelerating Mixture-of-Experts Multimodal Large Language Models via Dynamic Expert Skipping](https://arxiv.org/pdf/2511.15690)

**Yushi Huang**, Zining Wang, Zhihang Yuan📧, Yifu Ding, Ruihao Gong, Jinyang Guo, Xianglong Liu, Jun Zhang📧

<div style="display: inline">
    <a class="resource-link" href="https://arxiv.org/pdf/2511.15690">Paper</a>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/linvideo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LinVideo: A Post-Training Framework towards $\mathcal{O}(n)$ Attention in Efficient Video Generation](https://arxiv.org/pdf/2510.08318)

**Yushi Huang**, Xingtong Ge, Ruihao Gong📧, Chengtao Lv, Jun Zhang📧

<div style="display: inline">
    <a class="resource-link" href="https://arxiv.org/pdf/2510.08318">Paper</a>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/qvgen.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[QVGen: Pushing the Limit of Quantized Video Generative Models](https://arxiv.org/pdf/2505.11497)

**Yushi Huang**, Ruihao Gong📧, Jing Liu, Yifu Ding, Chengtao Lv, Haotong Qin, Jun Zhang📧

<div style="display: inline">
    <a class="resource-link" href="https://arxiv.org/pdf/2505.11497">Paper</a>
    <a class="resource-link" href="https://github.com/ModelTC/QVGen">Code</a>
</div>

</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2025</div><img src='images/temporal-feature-matters.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Temporal Feature Matters: A Framework for Diffusion Model Quantization](https://arxiv.org/pdf/2407.19547)

**Yushi Huang**, Ruihao Gong, Xianglong Liu📧, Jing Liu, Yuhang Li, Jiwen Lu, Dacheng Tao

<div style="display: inline">
    <a class="resource-link" href="https://arxiv.org/pdf/2407.19547">Paper</a>
    <a class="resource-link" href="https://github.com/ModelTC/TFMQ-DM">Code</a>
</div>

</div>
</div> -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/harmonica.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HarmoniCa: Harmonizing Training and Inference for Better Feature Caching in Diffusion Transformer Acceleration](https://arxiv.org/pdf/2410.01723)

**Yushi Huang\***, Zining Wang\*, Ruihao Gong📧, Jing Liu, Xinjie Zhang, Jinyang Guo, Xianglong Liu, Jun Zhang📧

<div style="display: inline">
    <a class="resource-link" href="https://arxiv.org/pdf/2410.01723">Paper</a>
  <a class="resource-link" href="https://github.com/ModelTC/HarmoniCa">Code</a>
</div>

</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024 Industry Track</div><img src='images/llmc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LLMC: Benchmarking Large Language Model Quantization with a Versatile Compression Toolkit](https://arxiv.org/pdf/2405.06001)

Ruihao Gong\*, Yang Yong\*, Shiqiao Gu\*, **Yushi Huang\***, Chengtao Lv, Yunchen Zhang, Dacheng Tao, Xianglong Liu📧

<div style="display: inline">
    <a class="resource-link" href="https://arxiv.org/pdf/2405.06001">Paper</a>
    <a class="resource-link" href="https://github.com/ModelTC/llmc">Code</a>
</div>

</div>
</div> -->

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024 Highlight</div><img src='images/tfmq-dm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TFMQ-DM: Temporal Feature Maintenance Quantization for Diffusion Models](https://arxiv.org/pdf/2311.16503)

**Yushi Huang\***, Ruihao Gong\*, Jing Liu, Tianlong Chen, Xianglong Liu📧

<div style="display: inline">
    <a class="resource-link" href="https://arxiv.org/pdf/2311.16503">Paper</a>
    <a class="resource-link" href="https://github.com/ModelTC/TFMQ-DM">Code</a>
    <a class="resource-link" href="https://modeltc.github.io/TFMQ-DM/">Project Page</a>
</div>

</div>
</div> -->

</div>

<span class='anchor' id='-projects'></span>
# Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Toolkit</div><img src='images/llmc_tool.png' alt="LightCompress" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LightCompress](https://github.com/ModelTC/LightCompress) is an off-the-shelf compression suite for AIGC models (LLMs, VLMs, diffusion, etc.) that packages SOTA quantization, sparsification, and deployment best practices to shrink models while preserving accuracy. **600+ GitHub Stars.**

<div style="display: inline">
    <a class="resource-link" href="https://github.com/ModelTC/LightCompress">GitHub</a>
</div>

</div>
</div>


<span class='anchor' id='-services'></span>
# Services
- Conference Reviews: NeurIPS, ICLR, ICML, COLM, AAAI, CVPR, ECCV.

<span class='anchor' id='-educations'></span>
# Educations
- *2025.02 - Now*, Ph.D. in Electronic Computer and Engineering, the Hong Kong University of Science and Technology.
- *2020.09 - 2024.06*, B.Eng. in Computer Science and Engineering, Shenyuan Honors College, Beihang University.

<span class='anchor' id='-internships'></span>
# Internships
- *2025.09-2025.11*, Bytedance Seed.
- *2024.12 - 2025.02*, Microsoft Research Asia.
- *2023.05 - Now*, SenseTime Research.

