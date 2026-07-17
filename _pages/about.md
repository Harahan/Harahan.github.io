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

<span class='anchor' id='about-me'></span>

I am a Ph.D. student at the Hong Kong University of Science and Technology (HKUST), supervised by Prof. [Jun Zhang](https://eejzhang.people.ust.hk/home.html). I received my B.E. degree from Beihang University. My research interest is building **efficient and high-performing generative systems**. I currently work on RL for efficient image/video generation. Previously, I worked on improving inference efficiency for vision and language generative models, including low-precision inference, computation skipping, efficient attention, etc.

I am always happy to chat about research and potential collaborations — feel free to [reach out](mailto:yh4717023@gmail.com).

<span class='anchor' id='-news'></span>
# News

<div class="news-box" markdown="1">
- *2026.06*: &nbsp;🎉🎉 Our SALT is accepted to ECCV.
- *2026.05*: &nbsp;🎉🎉 Our Light Forcing, SGMD, and Flash-VAED are accepted to ICML.
- *2026.04*: &nbsp;🎉🎉 Our LinVideo is selected as a Highlight Poster.
- *2026.04*: &nbsp;🎉🎉 Our Focus-dLLM is accepted to ACL (Main).
- *2026.02*: &nbsp;🎉🎉 Our MoDES and LinVideo are accepted to CVPR.
- *2026.01*: &nbsp;🎉🎉 Our QVGen is accepted to ICLR.
- *2025.11*: &nbsp;🎉🎉 Our SlimInfer and LLMC+ are accepted to AAAI.
- *2025.06*: &nbsp;🎉🎉 Our Temporal Feature Matters is accepted to TPAMI.
- *2025.05*: &nbsp;🎉🎉 Our HarmoniCa is accepted to ICML.
- *2024.10*: &nbsp;🎉🎉 Our LLMC is accepted to EMNLP Industry Track.
- *2024.07*: &nbsp;🎉🎉 Our PTSBench is accepted to ACM MM.
- *2024.02*: &nbsp;🎉🎉 Our TFMQ-DM is accepted to CVPR as a Highlight Poster.
</div>

<span class='anchor' id='-publications'></span>
# Publications

<p class="pub-legend">* equal contribution &nbsp;·&nbsp; 📧 corresponding author &nbsp;·&nbsp; full list sorted by date. <span id="gs-cite" class="gs-cite" hidden>Citations: <a href="https://scholar.google.com/citations?hl=en&user=9-FYp3EAAAAJ" target="_blank" rel="noopener"><span id="gs-cite-num"></span></a></span></p>

<div class="pub-tabs">
  <button class="pub-tab is-active" data-target="pub-selected" type="button">Selected</button>
  <button class="pub-tab" data-target="pub-all" type="button">Full List</button>
</div>

<div id="pub-selected" class="pub-view">

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026 Highlight</div><img src='images/linvideo.webp?v={{ site.time | date: "%s" }}' loading="lazy" decoding="async" alt="LinVideo" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LinVideo: A Post-Training Framework towards $\mathcal{O}(n)$ Attention in Efficient Video Generation](https://arxiv.org/abs/2510.08318)

**Yushi Huang**, Xingtong Ge, Ruihao Gong📧, Chengtao Lv, Jun Zhang📧

<div style="display: inline">
    <a class="resource-link" href="https://arxiv.org/abs/2510.08318">Paper</a>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/qvgen.webp?v={{ site.time | date: "%s" }}' loading="lazy" decoding="async" alt="QVGen" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[QVGen: Pushing the Limit of Quantized Video Generative Models](https://arxiv.org/abs/2505.11497)

**Yushi Huang**, Ruihao Gong📧, Jing Liu, Yifu Ding, Chengtao Lv, Haotong Qin, Jun Zhang📧

<div style="display: inline">
    <a class="resource-link" href="https://arxiv.org/abs/2505.11497">Paper</a>
    <a class="resource-link" href="https://github.com/ModelTC/QVGen">Code</a>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2026</div><img src='images/meanflownft.webp?v={{ site.time | date: "%s" }}' loading="lazy" decoding="async" alt="MeanFlowNFT" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MeanFlowNFT: Bringing Forward-Process RL to Average-Velocity Generators](https://arxiv.org/abs/2607.15273)

**Yushi Huang\***, Xiangxin Zhou\*📧, Jun Zhang, Liefeng Bo, Tianyu Pang📧

<div style="display: inline">
    <a class="resource-link" href="https://arxiv.org/abs/2607.15273">Paper</a>
    <a class="resource-link" href="https://github.com/Harahan/MeanFlowNFT">Code</a>
    <a class="resource-link" href="https://harahan.github.io/meanflownft-project-page/">Project</a>
    <a class="resource-link" href="https://huggingface.co/Harahan/MeanFlowNFT">Models</a>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/modes.webp?v={{ site.time | date: "%s" }}' loading="lazy" decoding="async" alt="MoDES" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MoDES: Accelerating Mixture-of-Experts Multimodal Large Language Models via Dynamic Expert Skipping](https://arxiv.org/abs/2511.15690)

**Yushi Huang**, Zining Wang, Zhihang Yuan📧, Yifu Ding, Ruihao Gong, Jinyang Guo, Xianglong Liu, Jun Zhang📧

<div style="display: inline">
    <a class="resource-link" href="https://arxiv.org/abs/2511.15690">Paper</a>
    <a class="resource-link" href="https://github.com/ModelTC/MoDES">Code</a>
</div>

</div>
</div>

</div>

<div id="pub-all" class="pub-view" hidden>
<div class="pub-list">

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">arXiv</span><span class="pub-venue-year">2026</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2607.15273" target="_blank" rel="noopener">MeanFlowNFT: Bringing Forward-Process RL to Average-Velocity Generators</a>
    <div class="pub-auth"><strong>Yushi Huang*</strong>, Xiangxin Zhou*📧, Jun Zhang, Liefeng Bo, Tianyu Pang📧</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2607.15273" target="_blank" rel="noopener">Paper</a><a href="https://github.com/Harahan/MeanFlowNFT" target="_blank" rel="noopener">Code</a><a href="https://harahan.github.io/meanflownft-project-page/" target="_blank" rel="noopener">Project</a><a href="https://huggingface.co/Harahan/MeanFlowNFT" target="_blank" rel="noopener">Models</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">arXiv</span><span class="pub-venue-year">2026</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2606.11075" target="_blank" rel="noopener">Exploring the Design Space of Reward Backpropagation for Flow Matching</a>
    <div class="pub-auth">Ruoyu Wang*, Boye Niu*, Xiangxin Zhou*, <strong>Yushi Huang</strong>, Tongliang Liu, Chi Zhang📧</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2606.11075" target="_blank" rel="noopener">Paper</a><a href="https://github.com/RuoyuWang-2077/FlowBP" target="_blank" rel="noopener">Code</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">arXiv</span><span class="pub-venue-year">2026</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2605.26108" target="_blank" rel="noopener">Reinforcing Few-step Generators via Reward-Tilted Distribution Matching</a>
    <div class="pub-auth"><strong>Yushi Huang*</strong>, Xiangxin Zhou*, Ruoyu Wang*, Chi Zhang, Jun Zhang, Tianyu Pang📧</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2605.26108" target="_blank" rel="noopener">Paper</a><a href="https://github.com/Harahan/RTDMD" target="_blank" rel="noopener">Code</a><a href="https://huggingface.co/collections/Harahan/rtdmd" target="_blank" rel="noopener">Models</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">ECCV</span><span class="pub-venue-year">2026</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2604.03118" target="_blank" rel="noopener">Salt: Self-Consistent Distribution Matching with Cache-Aware Training for Few-Step Video Generation</a>
    <div class="pub-auth">Xingtong Ge, Yi Zhang, <strong>Yushi Huang</strong>, Dailan He, Xiahong Wang, Bingqi Ma, Guanglu Song, Yu Liu, Jun Zhang📧</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2604.03118" target="_blank" rel="noopener">Paper</a><a href="https://github.com/XingtongGe/Salt" target="_blank" rel="noopener">Code</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">arXiv</span><span class="pub-venue-year">2026</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2603.15433" target="_blank" rel="noopener">Real-Time Human Frontal View Synthesis from a Single Image</a>
    <div class="pub-auth">Fangyu Lin, Yingdong Hu, Lunjie Zhu, Zhening Liu, <strong>Yushi Huang</strong>, Zehong Lin, Jun Zhang📧</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2603.15433" target="_blank" rel="noopener">Paper</a><a href="https://github.com/rslinfy/PrismMirror" target="_blank" rel="noopener">Code</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">ICML</span><span class="pub-venue-year">2026</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2605.30116" target="_blank" rel="noopener">SGMD: Score Gradient Matching Distillation for Few-Step Video Diffusion Distillation</a>
    <div class="pub-auth">Zhuguanyu Wu, Ruihao Gong📧, Yang Yong, <strong>Yushi Huang</strong>, Xiangyu Fan, Lei Yang, Dahua Lin, Xianglong Liu</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2605.30116" target="_blank" rel="noopener">Paper</a><a href="https://github.com/ModelTC/LightX2V" target="_blank" rel="noopener">Code</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">ICML</span><span class="pub-venue-year">2026</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2602.19161" target="_blank" rel="noopener">Flash-VAED: Plug-and-Play VAE Decoders for Efficient Video Generation</a>
    <div class="pub-auth">Lunjie Zhu, <strong>Yushi Huang</strong>, Xingtong Ge, Yufei Xue, Zhening Liu, Yumeng Zhang, Zehong Lin, Jun Zhang📧</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2602.19161" target="_blank" rel="noopener">Paper</a><a href="https://github.com/Aoko955/Flash-VAED" target="_blank" rel="noopener">Code</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">ICML</span><span class="pub-venue-year">2026</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2602.04789" target="_blank" rel="noopener">Light Forcing: Accelerating Autoregressive Video Diffusion via Sparse Attention</a>
    <div class="pub-auth">Chengtao Lv, Yumeng Shi, <strong>Yushi Huang</strong>, Ruihao Gong📧, Shen Ren, Wenya Wang📧</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2602.04789" target="_blank" rel="noopener">Paper</a><a href="https://github.com/chengtao-lv/LightForcing" target="_blank" rel="noopener">Code</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">ACL</span><span class="pub-venue-year">2026</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2602.02159" target="_blank" rel="noopener">Focus-dLLM: Accelerating Long-Context Diffusion LLM Inference via Confidence-Guided Context Focusing</a>
    <div class="pub-auth">Lingkun Long, <strong>Yushi Huang</strong>, Shihao Bai, Ruihao Gong, Jun Zhang, Ao Zhou, Jianlei Yang📧</div>
    <div class="pub-tag">Main Conference</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2602.02159" target="_blank" rel="noopener">Paper</a><a href="https://github.com/Longxmas/Focus-dLLM" target="_blank" rel="noopener">Code</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">CVPR</span><span class="pub-venue-year">2026</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2511.15690" target="_blank" rel="noopener">MoDES: Accelerating Mixture-of-Experts Multimodal Large Language Models via Dynamic Expert Skipping</a>
    <div class="pub-auth"><strong>Yushi Huang</strong>, Zining Wang, Zhihang Yuan📧, Yifu Ding, Ruihao Gong, Jinyang Guo, Xianglong Liu, Jun Zhang📧</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2511.15690" target="_blank" rel="noopener">Paper</a><a href="https://github.com/ModelTC/MoDES" target="_blank" rel="noopener">Code</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">CVPR</span><span class="pub-venue-year">2026</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2510.08318" target="_blank" rel="noopener">LinVideo: A Post-Training Framework towards O(n) Attention in Efficient Video Generation</a>
    <div class="pub-auth"><strong>Yushi Huang</strong>, Xingtong Ge, Ruihao Gong📧, Chengtao Lv, Jun Zhang📧</div>
    <div class="pub-tag">Highlight</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2510.08318" target="_blank" rel="noopener">Paper</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">AAAI</span><span class="pub-venue-year">2026</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2508.09981" target="_blank" rel="noopener">LLMC+: Benchmarking Vision-Language Model Compression with a Plug-and-play Toolkit</a>
    <div class="pub-auth">Chengtao Lv, Bilang Zhang, Yang Yong, Ruihao Gong📧, <strong>Yushi Huang</strong>, Shiqiao Gu, Jiajun Wu, Yumeng Shi, Jinyang Guo, Wenya Wang📧</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2508.09981" target="_blank" rel="noopener">Paper</a><a href="https://github.com/ModelTC/LightCompress" target="_blank" rel="noopener">Code</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">AAAI</span><span class="pub-venue-year">2026</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2508.06447" target="_blank" rel="noopener">SlimInfer: Accelerating Long-Context LLM Inference via Dynamic Token Pruning</a>
    <div class="pub-auth">Lingkun Long, Rubing Yang, <strong>Yushi Huang</strong>, Desheng Hui, Ao Zhou📧, Jianlei Yang📧</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2508.06447" target="_blank" rel="noopener">Paper</a><a href="https://github.com/Longxmas/SlimInfer" target="_blank" rel="noopener">Code</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">ICLR</span><span class="pub-venue-year">2026</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2505.11497" target="_blank" rel="noopener">QVGen: Pushing the Limit of Quantized Video Generative Models</a>
    <div class="pub-auth"><strong>Yushi Huang</strong>, Ruihao Gong📧, Jing Liu, Yifu Ding, Chengtao Lv, Haotong Qin, Jun Zhang📧</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2505.11497" target="_blank" rel="noopener">Paper</a><a href="https://github.com/ModelTC/QVGen" target="_blank" rel="noopener">Code</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">arXiv</span><span class="pub-venue-year">2025</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2512.00877" target="_blank" rel="noopener">Feed-Forward 3D Gaussian Splatting Compression with Long-Context Modeling</a>
    <div class="pub-auth">Zhening Liu*, Rui Song*, <strong>Yushi Huang</strong>, Yingdong Hu, Xinjie Zhang, Jiawei Shao, Zehong Lin, Jun Zhang📧</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2512.00877" target="_blank" rel="noopener">Paper</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">arXiv</span><span class="pub-venue-year">2025</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2508.03351" target="_blank" rel="noopener">Towards Efficient Post-Training Quantization for Large Vision-Language Models via Token-Wise Redundancy Elimination</a>
    <div class="pub-auth">Yufei Xue, <strong>Yushi Huang</strong>, Jiawei Shao, Jun Zhang📧</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2508.03351" target="_blank" rel="noopener">Paper</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">ICML</span><span class="pub-venue-year">2025</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2410.01723" target="_blank" rel="noopener">HarmoniCa: Harmonizing Training and Inference for Better Feature Caching in Diffusion Transformer Acceleration</a>
    <div class="pub-auth"><strong>Yushi Huang*</strong>, Zining Wang*, Ruihao Gong📧, Jing Liu, Xinjie Zhang, Jinyang Guo, Xianglong Liu, Jun Zhang📧</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2410.01723" target="_blank" rel="noopener">Paper</a><a href="https://github.com/ModelTC/HarmoniCa" target="_blank" rel="noopener">Code</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">TPAMI</span><span class="pub-venue-year">2025</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2407.19547" target="_blank" rel="noopener">Temporal Feature Matters: A Framework for Diffusion Model Quantization</a>
    <div class="pub-auth"><strong>Yushi Huang</strong>, Ruihao Gong, Xianglong Liu📧, Jing Liu, Yuhang Li, Jiwen Lu, Dacheng Tao</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2407.19547" target="_blank" rel="noopener">Paper</a><a href="https://github.com/ModelTC/TFMQ-DM" target="_blank" rel="noopener">Code</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">ACM MM</span><span class="pub-venue-year">2024</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2412.07268" target="_blank" rel="noopener">PTSBench: A Comprehensive Post-Training Sparsity Benchmark Towards Algorithms and Models</a>
    <div class="pub-auth">Zining Wang, Jinyang Guo, Ruihao Gong, Yang Yong, Aishan Liu, <strong>Yushi Huang</strong>, Jiaheng Liu, Xianglong Liu</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2412.07268" target="_blank" rel="noopener">Paper</a><a href="https://github.com/ModelTC/msbench" target="_blank" rel="noopener">Code</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">CVPR</span><span class="pub-venue-year">2024</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2311.16503" target="_blank" rel="noopener">TFMQ-DM: Temporal Feature Maintenance Quantization for Diffusion Models</a>
    <div class="pub-auth"><strong>Yushi Huang*</strong>, Ruihao Gong*, Jing Liu, Tianlong Chen, Xianglong Liu📧</div>
    <div class="pub-tag">Highlight</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2311.16503" target="_blank" rel="noopener">Paper</a><a href="https://github.com/ModelTC/TFMQ-DM" target="_blank" rel="noopener">Code</a><a href="https://modeltc.github.io/TFMQ-DM/" target="_blank" rel="noopener">Project</a></div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-venue"><span class="pub-venue-name">EMNLP</span><span class="pub-venue-year">2024</span></div>
  <div class="pub-main">
    <a class="pub-title" href="https://arxiv.org/abs/2405.06001" target="_blank" rel="noopener">LLMC: Benchmarking Large Language Model Quantization with a Versatile Compression Toolkit</a>
    <div class="pub-auth">Ruihao Gong*, Yang Yong*, Shiqiao Gu*, <strong>Yushi Huang*</strong>, Chengtao Lv, Yunchen Zhang, Xianglong Liu📧, Dacheng Tao</div>
    <div class="pub-tag">Industry Track</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2405.06001" target="_blank" rel="noopener">Paper</a><a href="https://github.com/ModelTC/llmc" target="_blank" rel="noopener">Code</a></div>
  </div>
</div>

</div>
</div>

<span class='anchor' id='-projects'></span>
# Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Toolkit</div><img src='images/llmc_tool.webp?v={{ site.time | date: "%s" }}' loading="lazy" decoding="async" alt="LightCompress" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LightCompress](https://github.com/ModelTC/LightCompress) is an off-the-shelf compression suite for AIGC models (LLMs, VLMs, diffusion, etc.) that packages SOTA quantization, sparsification, and deployment best practices to shrink models while preserving accuracy. **700+ GitHub Stars.**

<div style="display: inline">
    <a class="resource-link" href="https://github.com/ModelTC/LightCompress">GitHub</a>
</div>

</div>
</div>


<span class='anchor' id='-services'></span>
# Honors & Services
- **Conference Reviewer:** NeurIPS, ICLR, ICML, COLM, AAAI, CVPR, ECCV.

<span class='anchor' id='-educations'></span>
# Education

<div class="cv-list">

<div class="cv-item">
  <img class="cv-logo" src="images/logos/hkust.png" alt="HKUST">
  <div class="cv-info">
    <div class="cv-org">The Hong Kong University of Science and Technology</div>
    <div class="cv-role">Ph.D. in Electronic and Computer Engineering · Advised by Prof. Jun Zhang</div>
  </div>
  <div class="cv-date">2025.02 – Now</div>
</div>

<div class="cv-item">
  <img class="cv-logo" src="images/logos/beihang.png" alt="Beihang University">
  <div class="cv-info">
    <div class="cv-org">Beihang University</div>
    <div class="cv-role">B.Eng. in Computer Science and Technology · Shenyuan Honors College</div>
  </div>
  <div class="cv-date">2020.09 – 2024.06</div>
</div>

</div>

<span class='anchor' id='-experience'></span>
# Experience

<div class="cv-list">

<div class="cv-item">
  <img class="cv-logo" src="images/logos/hunyuan.png" alt="Tencent Hunyuan">
  <div class="cv-info">
    <div class="cv-org">Tencent · Hunyuan</div>
    <div class="cv-role">Research Intern</div>
    <div class="cv-note">RL for image/video generative models</div>
  </div>
  <div class="cv-date">2026.02 – Now</div>
</div>

<div class="cv-item">
  <img class="cv-logo" src="images/logos/seed.png" alt="ByteDance Seed">
  <div class="cv-info">
    <div class="cv-org">ByteDance · Seed</div>
    <div class="cv-role">Research Intern</div>
    <div class="cv-note">Inference acceleration for multimodal LLMs</div>
  </div>
  <div class="cv-date">2025.09 – 2025.11</div>
</div>

<!--
<div class="cv-item">
  <img class="cv-logo" src="images/logos/microsoft.png" alt="Microsoft Research Asia">
  <div class="cv-info">
    <div class="cv-org">Microsoft Research Asia</div>
    <div class="cv-role">Research Intern</div>
    <div class="cv-note">Video generation and world models</div>
  </div>
  <div class="cv-date">2024.12 – 2025.02</div>
</div>
-->

<div class="cv-item">
  <img class="cv-logo" src="images/logos/sensetime.png" alt="SenseTime Research">
  <div class="cv-info">
    <div class="cv-org">SenseTime Research</div>
    <div class="cv-role">Research Intern</div>
    <div class="cv-note">Compression and acceleration for image/video diffusion models and LLMs</div>
  </div>
  <div class="cv-date">2023.05 – 2025.03</div>
</div>

</div>
