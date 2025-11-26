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

I am a 1st-year Ph.D. student at the Hong Kong University of Science and Technology (HKUST), supervised by Prof. [Jun Zhang](https://eejzhang.people.ust.hk/home.html). I received my B.E. degree from Beihang University. I also work as a research intern at SenseTime Research, closely with Dr. [Ruihao Gong](https://xhplus.github.io/). Previously, I have interned at Microsoft Research Asia and SenseTime Research. My research interest focuses on *efficient vision and language generative models*.


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

<span class='anchor' id='-publications'></span>
# Selected Publications 
<span style="color:#6a737d">* indicates equal contribution, 📧 indicates corresponding author</span>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/modes.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MoDES: Accelerating Mixture-of-Experts Multimodal Large Language Models via Dynamic Expert Skipping](https://arxiv.org/pdf/2511.15690)

**Yushi Huang**, Zining Wang, Zhihang Yuan📧, Yifu Ding, Ruihao Gong, Jinyang Guo, Xianglong Liu, Jun Zhang📧

<div style="display: inline">
    <a class="resource-link" href="https://arxiv.org/pdf/2511.15690">Paper</a>
    <a class="fakelink" onclick="$(this).siblings('.abstract').slideToggle()">Abstract</a>
    <div class="abstract"  style="overflow: hidden; display: none;">
        <p> Mixture-of-Experts (MoE) Multimodal large language models (MLLMs) excel at vision–language tasks, but they suffer from high computational inefficiency. To reduce inference overhead, expert skipping methods have been proposed to deactivate redundant experts based on the current input tokens. However, we find that applying these methods—originally designed for unimodal large language models (LLMs)—to MLLMs results in considerable performance degradation. This is primarily because such methods fail to account for the heterogeneous contributions of experts across MoE layers and modality-specific behaviors of tokens within these layers. Motivated by these findings, we propose MoDES, the first training-free framework that adaptively skips experts to enable efficient and accurate MoE MLLM inference. It incorporates a globally-modulated local gating (GMLG) mechanism that integrates global layer-wise importance into local routing probabilities to accurately estimate per-token expert importance. A dual-modality thresholding (DMT) method is then applied, which processes tokens from each modality separately, to derive the skipping schedule. To set the optimal thresholds, we introduce a frontier search algorithm that exploits monotonicity properties, cutting convergence time from several days to a few hours. Extensive experiments for 3 model series across 13 benchmarks demonstrate that MoDES far outperforms previous approaches. For instance, when skipping $88\%$ experts for Qwen3-VL-MoE-30B-A3B-Instruct, the performance boost is up to $10.67\%$ ($97.33\%$ vs. $86.66\%$). Furthermore, MoDES significantly enhances inference speed, improving the prefilling time by $2.16\times$
        and the decoding time by $1.26\times$.  </p>
    </div>
</div>

</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/linvideo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LinVideo: A Post-Training Framework towards $\mathcal{O}(n)$ Attention in Efficient Video Generation](https://arxiv.org/pdf/2510.08318)

**Yushi Huang**, Xingtong Ge, Ruihao Gong📧, Chengtao Lv, Jun Zhang📧

<div style="display: inline">
    <a class="resource-link" href="https://arxiv.org/pdf/2510.08318">Paper</a>
    <a class="fakelink" onclick="$(this).siblings('.abstract').slideToggle()">Abstract</a>
    <div class="abstract"  style="overflow: hidden; display: none;">
        <p> Video diffusion models (DMs) have enabled high-quality video synthesis. However, their computation costs scale quadratically with sequence length because self-attention has quadratic complexity. While linear attention lowers the cost, fully replacing quadratic attention requires expensive pretraining due to the limited expressiveness of linear attention and the complexity of spatiotemporal modeling in video generation. In this paper, we present LinVideo, an efficient data-free post-training framework that replaces a target number of self-attention modules with linear attention while preserving the original model's performance. First, we observe a significant disparity in the replaceability of different layers. Instead of manual or heuristic choices, we frame layer selection as a binary classification problem and propose selective transfer, which automatically and progressively converts layers to linear attention with minimal performance impact. Additionally, to overcome the ineffectiveness and inefficiency of existing objectives for this transfer process, we introduce an anytime distribution matching (ADM) objective that aligns the distributions of samples across any timestep along the sampling trajectory. This objective is efficient and recovers model performance. Extensive experiments show that our method achieves a $1.25$-$2.00\times$ speedup while preserving generation quality, and our 4-step distilled model further delivers a $15.92\times$ latency reduction with minimal visual quality drop.  </p>
    </div>
</div>

</div>
</div> -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/qvgen.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[QVGen: Pushing the Limit of Quantized Video Generative Models](https://arxiv.org/pdf/2505.11497)

**Yushi Huang**, Ruihao Gong📧, Jing Liu, Yifu Ding, Chengtao Lv, Haotong Qin, Jun Zhang📧

<div style="display: inline">
    <a class="resource-link" href="https://arxiv.org/pdf/2505.11497">Paper</a>
    <a class="fakelink" onclick="$(this).siblings('.abstract').slideToggle()">Abstract</a>
    <div class="abstract"  style="overflow: hidden; display: none;">
        <p> Video diffusion models (DMs) have enabled high-quality video synthesis. Yet, their substantial computational and memory demands pose serious challenges to real-world deployment, even on high-end GPUs. As a commonly adopted solution, quantization has proven notable success in reducing cost for image DMs, while its direct application to video DMs remains ineffective. In this paper, we present QVGen, a novel quantization-aware training (QAT) framework tailored for high-performance and inference-efficient video DMs under extremely low-bit quantization (e.g., 4-bit or below). We begin with a theoretical analysis demonstrating that reducing the gradient norm is essential to facilitate convergence for QAT. To this end, we introduce auxiliary modules ($\Phi$) to mitigate large quantization errors, leading to significantly enhanced convergence. To eliminate the inference overhead of $\Phi$, we propose a rank-decay strategy that progressively eliminates $\Phi$. Specifically, we repeatedly employ singular value decomposition (SVD) and a proposed rank-based regularization $\gamma$ to identify and decay low-contributing components. This strategy retains performance while zeroing out inference overhead. Extensive experiments across $4$ state-of-the-art (SOTA) video DMs, with parameter sizes ranging from $1.3$B$\sim14$B, show that QVGen is the first to reach full-precision comparable quality under 4-bit settings. Moreover, it significantly outperforms existing methods. For instance, our 3-bit CogVideoX-2B achieves improvements of $+25.28$ in Dynamic Degree and $+8.43$ in Scene Consistency on VBench. </p>
    </div>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2025</div><img src='images/temporal-feature-matters.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Temporal Feature Matters: A Framework for Diffusion Model Quantization](https://arxiv.org/pdf/2407.19547) <img src='https://img.shields.io/github/stars/ModelTC/TFMQ-DM.svg?style=social&label=Star&maxAge=60' alt="sym" height="100%">

**Yushi Huang**, Ruihao Gong, Xianglong Liu📧, Jing Liu, Yuhang Li, Jiwen Lu, Dacheng Tao

<div style="display: inline">
    <a class="resource-link" href="https://arxiv.org/pdf/2407.19547">Paper</a>
    <a class="resource-link" href="https://github.com/ModelTC/TFMQ-DM">Code</a>
    <a class="fakelink" onclick="$(this).siblings('.abstract').slideToggle()">Abstract</a>
    <div class="abstract"  style="overflow: hidden; display: none;">
        <p> The Diffusion models, widely used for image generation, face significant challenges related to their broad applicability due to prolonged inference times and high memory demands. Efficient Post-Training Quantization (PTQ) is crucial to address these issues. However, unlike traditional models, diffusion models critically rely on the time-step for the multi-round denoising. Typically, each timestep is encoded into a hypersensitive temporal feature by several modules. Despite this, existing PTQ methods do not optimize these modules individually. Instead, they employ unsuitable reconstruction objectives and complex calibration methods, leading to significant disturbances in the temporal feature and denoising trajectory, as well as reduced compression efficiency. To address these challenges, we introduce a novel quantization framework that includes three strategies: 1) TIB-based Maintenance: Based on our innovative Temporal Information Block (TIB) definition, Temporal Information-aware Reconstruction (TIAR) and Finite Set Calibration (FSC) are developed to efficiently align original temporal features. 2) Cache-based Maintenance: Instead of indirect and complex optimization for the related modules, pre-computing and caching quantized counterparts of temporal features are developed to minimize errors. 3) Disturbance-aware Selection: Employ temporal feature errors to guide a fine-grained selection between the two maintenance strategies for further disturbance reduction. This framework preserves most of the temporal information and ensures high-quality end-to-end generation. Extensive testing on various datasets, diffusion models, and hardware confirms our superior performance and acceleration. </p>
    </div>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/harmonica.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HarmoniCa: Harmonizing Training and Inference for Better Feature Caching in Diffusion Transformer Acceleration](https://arxiv.org/pdf/2410.01723) <img src='https://img.shields.io/github/stars/ModelTC/HarmoniCa.svg?style=social&label=Star&maxAge=60' alt="sym" height="100%">

**Yushi Huang\***, Zining Wang\*, Ruihao Gong📧, Jing Liu, Xinjie Zhang, Jinyang Guo, Xianglong Liu, Jun Zhang📧

<div style="display: inline">
    <a class="resource-link" href="https://arxiv.org/pdf/2410.01723">Paper</a>
  <a class="resource-link" href="https://github.com/ModelTC/HarmoniCa">Code</a>
    <a class="fakelink" onclick="$(this).siblings('.abstract').slideToggle()">Abstract</a>
    <div class="abstract"  style="overflow: hidden; display: none;">
        <p> Diffusion Transformers (DiTs) excel in generative tasks but face practical deployment challenges due to high inference costs. Feature caching, which stores and retrieves redundant computations, offers the potential for acceleration. Existing learning-based caching, though adaptive, overlooks the impact of the prior timestep. It also suffers from misaligned objectives-aligned predicted noise vs. high-quality images-between training and inference. These two discrepancies compromise both performance and efficiency. To this end, we harmonize training and inference with a novel learning-based caching framework dubbed HarmoniCa. It first incorporates Step-Wise Denoising Training (SDT) to ensure the continuity of the denoising process, where prior steps can be leveraged. In addition, an Image Error Proxy-Guided Objective (IEPO) is applied to balance image quality against cache utilization through an efficient proxy to approximate the image error. Extensive experiments across $8$ models, $4$ samplers, and resolutions from $256\times256$ to $2K$ demonstrate superior performance and speedup of our framework. For instance, it achieves over $40\%$ latency reduction (i.e., $2.07\times$ theoretical speedup) and improved performance on PixArt-$\alpha$. Remarkably, our image-free approach reduces training time by $25\%$ compared with the previous method. </p>
    </div>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024 Highlight</div><img src='images/tfmq-dm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TFMQ-DM: Temporal Feature Maintenance Quantization for Diffusion Models](https://arxiv.org/pdf/2311.16503) <img src='https://img.shields.io/github/stars/ModelTC/TFMQ-DM.svg?style=social&label=Star&maxAge=60' alt="sym" height="100%">

**Yushi Huang\***, Ruihao Gong\*, Jing Liu, Tianlong Chen, Xianglong Liu📧

<div style="display: inline">
    <a class="resource-link" href="https://arxiv.org/pdf/2311.16503">Paper</a>
    <a class="resource-link" href="https://github.com/ModelTC/TFMQ-DM">Code</a>
    <a class="fakelink" onclick="$(this).siblings('.abstract').slideToggle()">Abstract</a>
    <div class="abstract"  style="overflow: hidden; display: none;">
        <p> The Diffusion model, a prevalent framework for image generation, encounters significant challenges in terms of broad applicability due to its extended inference times and substantial memory requirements. Efficient Post-training Quantization (PTQ) is pivotal for addressing these issues in traditional models. Different from traditional models, diffusion models heavily depend on the time-step $t$ to achieve satisfactory multi-round denoising. Usually, $t$ from the finite set $\{1, \ldots, T\}$ is encoded to a temporal feature by a few modules totally irrespective of the sampling data. However, existing PTQ methods do not optimize these modules separately. They adopt inappropriate reconstruction targets and complex calibration methods, resulting in a severe disturbance of the temporal feature and denoising trajectory, as well as a low compression efficiency. To solve these, we propose a Temporal Feature Maintenance Quantization (TFMQ) framework building upon a Temporal Information Block which is just related to the time-step $t$ and unrelated to the sampling data. Powered by the pioneering block design, we devise temporal information aware reconstruction (TIAR) and finite set calibration (FSC) to align the full-precision temporal features in a limited time. Equipped with the framework, we can maintain the most temporal information and ensure the end-to-end generation quality. Extensive experiments on various datasets and diffusion models prove our state-of-the-art results. Remarkably, our quantization approach, for the first time, achieves model performance nearly on par with the full-precision model under 4-bit weight quantization. Additionally, our method incurs almost no extra computational cost and accelerates quantization time by $2.0\times$ on LSUN-Bedrooms $256\times 256$ compared to previous works.  </p>
    </div>
    <a class="resource-link" href="https://modeltc.github.io/TFMQ-DM/">Project Page</a>
</div>

</div>
</div>


<span class='anchor' id='-projects'></span>
# Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Toolkit</div><img src='images/llmc.png' alt="LightCompress" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LightCompress](https://github.com/ModelTC/LightCompress) is an off-the-shelf compression suite for AIGC models (LLMs, VLMs, diffusion, etc.) that packages SOTA quantization, sparsification, and deployment best practices to shrink models while preserving accuracy.

<div style="display: inline">
    <a class="resource-link" href="https://github.com/ModelTC/LightCompress">GitHub</a>
</div>

</div>
</div>


<span class='anchor' id='-services'></span>
# Services
- Conference Reviews: NeurIPS, ICLR, ICML, COLM, AAAI, CVPR.

<span class='anchor' id='-educations'></span>
# Educations
- *2025.02 - Now*, Ph.D. in Electronic Computer and Engineering, the Hong Kong University of Science and Technology.
- *2020.09 - 2024.06*, B.Eng. in Computer Science and Engineering, Shenyuan Honors College, Beihang University.

<span class='anchor' id='-internships'></span>
# Internships
- *2025.02 - Now*, SenseTime Research.
- *2024.12 - 2025.02*, Microsoft Research Asia.
- *2023.05 - 2024.12*, SenseTime Research.
