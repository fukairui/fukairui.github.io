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

# 👋 About Me

I received both my M.S. and B.S. degrees in Computer Science and Technology from Zhejiang University, where I was advised by Prof. [Kun Kuang](https://kunkuang.github.io/) and Prof. [Shengyu Zhang](https://scholar.google.com/citations?user=l4Dyt7EAAAAJ&hl=en). Additionally, I was fortunate to conduct research on generative retrieval for recommendation at the Taobao & Tmall Group, Alibaba.

My research focuses on generalizability and personalization in recommender systems. I am particularly interested in LLM-based recommendation and efficient inference for large-scale systems serving long user interaction sequences. I also study how heterogeneous models can be integrated effectively across mobile devices and cloud infrastructure.


# 🔥 News
- *2026.05*: &nbsp;🎉🎉 One paper was accepted to KDD 2026.
- *2026.02*: &nbsp;📰📰 One paper on rank-enhanced generative retrieval with listwise DPO was deployed on Taobao and is available on arXiv.
- *2026.01*: &nbsp;🎉🎉 Three papers were accepted to the research, industry, and short-paper tracks of TheWebConf 2026.
- *2026.01*: &nbsp;📰📰 One paper on efficient inference for large sequential recommendation is now available on arXiv.
- *2025.07*: &nbsp;🎉🎉 Two papers have been accepted to MM 2025.
- *2024.12*: &nbsp;🎉🎉 One paper has been accepted to AAAI 2025.
- *2024.11*: &nbsp;🎉🎉 One paper has been accepted to KDD 2025.
- *2024.08*: &nbsp;🥳🥳 I attended KDD in Barcelona, Spain, where I gave an oral presentation on our paper DIET.
- *2024.05*: &nbsp;🎉🎉 One paper was accepted to KDD 2024.
- *2023.07*: &nbsp;🥳🥳 I attended CICAI in Fuzhou, China, gave an oral presentation, and received the Best Paper Award.
- *2023.06*: &nbsp;🎉🎉 One paper was accepted to CICAI 2023.

# 📝 Publications


*\* denotes equal contribution.*

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2026</div><img src="{{ '/images/FORGE.png' | relative_url }}" alt="FORGE paper illustration" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[FORGE: Forming Semantic Identifiers for Generative Retrieval in Industrial Datasets](https://arxiv.org/abs/2509.20904)

**Kairui Fu\***, Tao Zhang\*, Shuwen Xiao\*, Ziyang Wang, Xinming Zhang, Chenchi Zhang, Yuliang Yan, Junjun Zheng, Xiangheng Kong, Shengyu Zhang, Kun Kuang, Yuning Jiang

[Hugging Face](https://huggingface.co/AL-GR) [GitHub](https://github.com/selous123/al_sid) [知乎](https://zhuanlan.zhihu.com/p/1956015687244952683) [WeChat](https://mp.weixin.qq.com/s/c9oShjkLwmIzutzpcVxu6w)

- Investigate what constitutes better semantic identifiers through a taxonomy of SID construction strategies and extensive downstream GR validation.
- Release AL-GR, an industrial-scale Taobao dataset with 14 billion interactions and multimodal features of 250 million items.
- Deployed on Taobao’s "Guess You Like" section, FORGE achieved a 0.35% increase in online transaction count.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src="{{ '/images/RankGR.png' | relative_url }}" alt="RankGR paper illustration" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[RankGR: Rank-Enhanced Generative Retrieval with Listwise Direct Preference Optimization in Recommendation](https://arxiv.org/abs/2602.08575v1)

**Kairui Fu\***, Changfa Wu\*, Kun Yuan, Binbin Cao, Dunxian Huang, Yuliang Yan, Junjun Zheng, Jianning Zhang, Silu Zhou, Jian Wu, Kun Kuang

- Enhance generative retrieval with listwise DPO and lightweight rescoring to capture hierarchical preferences and richer user-item interactions.
- Deployed on Taobao’s "Guess You Like" section, RankGR achieved a 1.08% increase in online item page views and captured 49.88% of total exposures.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TheWebConf 2026</div><img src="{{ '/images/PI2I.png' | relative_url }}" alt="PI2I paper illustration" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[PI2I: A Personalized Item-Based Collaborative Filtering Retrieval Framework](https://arxiv.org/abs/2601.16815)

Shaoqing Wang\*, Yingcai Ma\*, **Kairui Fu\***, Ziyang Wang, Dunxian Huang, Yuliang Yan, Jian Wu

[Hugging Face](https://huggingface.co/datasets/PI2I/PI2I)

- A novel two-stage retrieval framework that enhances the personalization capabilities of traditional collaborative filtering.
- Deployed on Taobao’s "Guess You Like" section, PI2I achieved a 1.05% increase in online transaction rates.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TheWebConf 2026</div><img src="{{ '/images/thinkrec.png' | relative_url }}" alt="ThinkRec paper illustration" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[ThinkRec: Thinking-based recommendation via LLM](https://arxiv.org/abs/2505.15091)

Qihang Yu\*, **Kairui Fu\***, Shengyu Zhang, Zheqi Lv, Fan Wu, Fei Wu

[Project](https://github.com/Yu-Qi-hang/ThinkRec)

- An early attempt to activate the reasoning ability of LLMs for more interpretable and effective recommendation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TheWebConf 2026</div><img src="{{ '/images/RASTP.png' | relative_url }}" alt="RASTP paper illustration" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[RASTP: Representation-Aware Semantic Token Pruning for Generative Recommendation with Semantic Identifiers](https://arxiv.org/abs/2511.16943)

Tianyu Zhan\*, **Kairui Fu\***, Zheqi Lv, Shengyu Zhang

[Project](https://github.com/Yuzt-zju/RASTP)

- An effective strategy to selectively prune less informative tokens for semantic-identifier-based recommendation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src="{{ '/images/MALLOC.png' | relative_url }}" alt="MALLOC paper illustration" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[MALLOC: Benchmarking the Memory-aware Long Sequence Compression for Large Sequential Recommendation](https://arxiv.org/abs/2601.20234)

Qihang Yu\*, **Kairui Fu\***, Zhaocheng Du\*, Yuxuan Si, Kaiyuan Li, Weihao Zhao, Zhicheng Zhang, Jieming Zhu, Quanyu Dai, Zhenhua Dong, Shengyu Zhang, Kun Kuang, Fei Wu

[Project](https://anonymous.4open.science/r/MALLOC)

- A benchmark that establishes a rigorous multi-dimensional evaluation protocol that couples standard ranking metrics with system-level constraints for long-sequence compression in large recommender systems.
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MM 2025</div><img src="{{ '/images/CHORD.png' | relative_url }}" alt="CHORD paper illustration" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[CHORD: Customizing Hybrid-precision On-device Model for Sequential Recommendation with Device-cloud Collaboration](https://dl.acm.org/doi/10.1145/3746027.3755632)

Tianqi Liu\*, **Kairui Fu\***, Shengyu Zhang, Wenyan Fan, Zhaocheng Du, Jieming Zhu, Fan Wu, Fei Wu

- A device-cloud collaborative framework for personalized mixed-precision quantization that generates lightweight networks for heterogeneous mobile devices.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MM 2025</div><img src="{{ '/images/Persona.png' | relative_url }}" alt="Prototype-based parameter editing paper illustration" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[Tackling Device Data Distribution Real-time Shift via Prototype-based Parameter Editing](https://dl.acm.org/doi/10.1145/3746027.3754895)

Zheqi Lv, Wenqiao Zhang, **Kairui Fu**, Qi Tian, Shengyu Zhang, Jiajie Su, Jingyuan Chen, Kun Kuang, Fei Wu

- Prototype-based parameter editing for tackling real-time distribution shifts on devices in both vision and recommendation tasks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2025</div><img src="{{ '/images/Forward-OFA.png' | relative_url }}" alt="Forward Once for All paper illustration" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[Forward Once for All: Structural Parameterized Adaptation for Efficient Cloud-coordinated On-device Recommendation](https://dl.acm.org/doi/10.1145/3690624.3709178)

**Kairui Fu**, Zheqi Lv, Shengyu Zhang, Fan Wu, Kun Kuang

[Project](https://gitee.com/ouo-ovo/forward-ofa/)

- An early attempt at jointly customizing model structures and parameters for efficient cloud-coordinated on-device recommendation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src="{{ '/images/MergeNet.png' | relative_url }}" alt="MergeNet paper illustration" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[MergeNet: Knowledge Migration across Heterogeneous Models, Tasks, and Modalities](https://ojs.aaai.org/index.php/AAAI/article/view/32510)

Kunxi Li\*, Tianyu Zhan\*, **Kairui Fu\***, Shengyu Zhang, Kun Kuang, Jiwei Li, Zhou Zhao, Fan Wu, Fei Wu

[Project](https://github.com/Fantasylii/mergenet) [知乎](https://zhuanlan.zhihu.com/p/20574047950) [WeChat](https://mp.weixin.qq.com/s/I8IP2scMsRatnGChpR8sWQ)

- Leverage parameters as the medium to achieve knowledge transfer across heterogeneous models, tasks, and modalities.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2024</div><img src="{{ '/images/DIET.png' | relative_url }}" alt="DIET paper illustration" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[DIET: Customized Slimming for Incompatible Networks in Sequential Recommendation](https://dl.acm.org/doi/abs/10.1145/3637528.3671669)

**Kairui Fu**, Shengyu Zhang, Zheqi Lv, Jingyuan Chen, Jiwei Li

- Tackle parameter personalization and communication efficiency under strict device constraints in device-cloud collaborative recommendation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CICAI 2023 <b>Best Paper</b></div><img src="{{ '/images/CICAI.png' | relative_url }}" alt="CICAI paper illustration" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[End-to-End Optimization of Quantization-Based Structure Learning and Interventional Next-Item Recommendation](https://link.springer.com/chapter/10.1007/978-981-99-8850-1_34)

**Kairui Fu**, Qiaowei Miao, Shengyu Zhang, Kun Kuang, Fei Wu

- Investigate user distribution shifts in recommender systems and the difficulty of causal structure learning under recommender-system interventions.
</div>
</div>

# 🎖 Honors and Awards
- *2026.03* Outstanding Graduate of Zhejiang Province
- *2025.10* National Scholarship (Top 1%)
- *2024.12* Huawei Jingying Scholarship (Top 1%)
- *2023.07* Best Paper Award at CICAI 2023 (Top 1)
- *2023.06* Outstanding Graduate of Zhejiang University
- *2020–2022* Scholarship of Zhejiang University (three consecutive years)


# 📖 Education
- *2023.09 - 2026.03*, M.S. in Computer Science and Technology, Zhejiang University, Hangzhou.
- *2019.09 - 2023.06*, B.S. in Computer Science and Technology, Turing Class (Chu Kochen Honors College), Zhejiang University, Hangzhou


# 💻 Internships
- *2025.02 - 2025.05*, [Huawei Noah’s Ark Lab](http://dev3.noahlab.com.hk/index.html), China.
- *2025.05 - 2026.03*, [Taobao & Tmall Group of Alibaba](https://ali-home.alibaba.com/en-us/), China.
