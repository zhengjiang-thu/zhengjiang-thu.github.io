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

I am a second year PhD student studying at the Department of Computer Science and Technology, [Tsinghua University](https://www.tsinghua.edu.cn/), advised by [Prof. Lifeng Sun](https://scholar.google.com/citations?user=GySPN6oAAAAJ). I received my bachelor's degree from [Tsinghua University](https://www.tsinghua.edu.cn/) in June 2024.
My research interests primarily lie in the field of agentic reinforcement learning and multi-agent collaboration.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>1000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- **2026.02**: &nbsp;🎉 One paper accepted by CVPR 2026.
- **2026.01**: &nbsp;🎉 Two papers accepted by ICLR 2026.

# 📖 Educations
- <img src='images/logos/tsinghua.png' style='height: 28px; vertical-align: middle; margin-right: 6px;'> **2024.09 - Present**, Ph.D. @ Department of Computer Science and Technology, Tsinghua University.
- <img src='images/logos/tsinghua.png' style='height: 28px; vertical-align: middle; margin-right: 6px;'> **2020.09 - 2024.06**, B.Eng @ Department of Computer Science and Technology, Tsinghua University.

# 💻 Internships
- <img src='images/logos/damo.png' style='height: 28px; vertical-align: middle; margin-right: 6px;'> **2024.11 - Present**, Research Intern @ DAMO Academy, Alibaba Group

# 📝 Publications 

## Selected Publications:

_${\*}$ Equal contribution, ${\dagger}$ Corresponding author_

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/publications/medvr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MedVR: Annotation-Free Medical Visual Reasoning via Agentic Reinforcement Learning](https://arxiv.org/pdf/2604.08203v1)

**Zheng Jiang$^{\*}$**, Heng Guo$^{\*}$, Chengyu Fang$^{\*}$, Changchen Xiao, Xinyang Hu, Lifeng Sun$^{\dagger}$, Minfeng Xu$^{\dagger}$

- MedVR is the first end-to-end reinforcement learning framework that seamlessly integrates visual and textual reasoning for medical VLMs, obviating the need for costly intermediate supervision.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/publications/subflot.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SubFLOT: Submodel Extraction for Efficient and Personalized Federated Learning via Optimal Transport](https://arxiv.org/pdf/2604.06631)

**Zheng Jiang**, Nan He, Yiming Chen, Lifeng Sun$^{\dagger}$

- SubFLOT is a server-side personalized federated pruning framework that leverages optimal transport and adaptive regularization to address system and statistical heterogeneity without accessing local data.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2026</div><img src='images/publications/ttsp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Test-time Scaling over Perception: Resolving the Grounding Paradox in Thinking with Images](todo)

**Zheng Jiang**, Yiming Chen, Nan He, Jiahui Chen, Chaoyang Li, Houde Qian, Lifeng Sun$^{\dagger}$

- TTSP is a test-time scaling framework that resolves the grounding paradox in tool-augmented visual reasoning by scaling perception through parallel exploration, reliability filtering, and iterative knowledge refinement.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2025</div><img src='images/publications/m3ret.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[M3Ret: Unleashing Zero-shot Multimodal Medical Image Retrieval via Self-Supervision](https://arxiv.org/pdf/2509.01360)

Che Liu$^{\*}$, **Zheng Jiang$^{\*}$**, Chengyu Fang$^{\*}$, Heng Guo, Yan-Jie Zhou, Jiaqi Qu, Le Lu, Minfeng Xu$^{\dagger}$

- A unified visual encoder without any modality-specific customization for various medical visual modalities in 2D and 3D.
</div>
</div>


## More Publications:

- Photon: Speedup Volume Understanding with Efficient Multimodal Large Language Models, **ICLR 2026** [[PDF]](https://arxiv.org/pdf/2603.25155). Chengyu Fang, Heng Guo, **Zheng Jiang**, Chunming He, Xiu Li$^{\dagger}$, Minfeng Xu$^{\dagger}$

- DynFed: Adaptive Federated Learning via Quantization-Aware Knowledge Distillation, **ACM MM 2025** [[PDF]](https://dl.acm.org/doi/pdf/10.1145/3746027.3755451). Nan He, Yiming Chen, **Zheng Jiang**, Song Yang, Lifeng Sun$^{\dagger}$

- FedSA-LoRA: Federated LoRA Fine-Tuning via Subspace Alignment. Yiming Chen, **Zheng Jiang**, Nan He, Lifeng Sun$^{\dagger}$

- SDFed: Sensitivity-Aware Differential Privacy and Multi-Teacher Distillation in Federated Learning. Nan He, Juan Fang, Yiming Chen, **Zheng Jiang**, Song Yang, Lifeng Sun$^{\dagger}$

- FedICL-KVc: Federated In-Context Learning via KV Cache. Yiming Chen, Nan He, **Zheng Jiang**, Lifeng Sun$^{\dagger}$

- MotionFlow: Real-Time Video Stylization via Motion-Guided Sparse Computation. Jiahui Chen, Rui Zhu, Qian Houde, **Zheng Jiang**, Yue Huang, Zhenan Lin, Chao Zhou, Lifeng Sun$^{\dagger}$


# 🎖 Honors and Awards
- **2024.06**: Outstanding Graduates of Department of Computer Science and Technology, Tsinghua University
- **2021-2023**: Academic Excellence Scholarship, Tsinghua University

# 💬 Invited Talks
- **2026.04**, "MedVR: Annotation-Free Medical Visual Reasoning via Agentic Reinforcement Learning", AI TIME.