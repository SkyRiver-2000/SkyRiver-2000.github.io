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

I am a first-year CS Ph.D. student at National University of Singapore (NUS), supervised by [Prof. Min-Yen Kan](https://www.comp.nus.edu.sg/~kanmy/) and [Prof. Soujanya Poria](https://soujanyaporia.github.io/). Previously, I obtained my Master's degree in Computer Science and Bachelor's degree in Inforamtion Engineering from Shanghai Jiao Tong University (SJTU), fortunately advised by [Prof. Weinan Zhang](https://wnzhang.net).

Recently, my research mainly focus on LLM reasoning and AI agents, especially:
* Reinforcement learning for reasoning models and agentic LLMs.
* LLM with memory augmentation for long context understanding.
* LLM-based multi-agent collaboration and competition.

**I am actively looking for 2026 summer research internship in U.S. and Mainland China!** Feel free to reach out to me if there is an opportunity or you are interested in academic discussion / collaboration.

# 🔥 News
- *2025.10*: &nbsp;🎉🎉 I will attend EMNLP 2025 at Suzhou during Nov 5-7, 2025. Let's connect!
- *2025.07*: &nbsp;🎉🎉 [**AntiLeak-Bench**](https://arxiv.org/pdf/2412.13670) is selected as SAC Highlight at ACL 2025!
- *2025.06*: &nbsp;🎉🎉 I will present our work [**RuleArena**](https://arxiv.org/pdf/2412.08972) and [**AntiLeak-Bench**](https://arxiv.org/pdf/2412.13670) at ACL 2025 in Vienna, Austria.
- *2025.05*: &nbsp;🎉🎉 Two papers [**RuleArena**](https://arxiv.org/pdf/2412.08972) and [**AntiLeak-Bench**](https://arxiv.org/pdf/2412.13670) are accepted by **ACL 2025 (Main)**.
- *2025.04*: &nbsp;🎉🎉 I will present our work [**RuleArena**](https://arxiv.org/pdf/2412.08972) at ICLR 2025 Workshops (Reason&Plan, SCI-FM). Hope to see you there.
- *2025.04*: &nbsp;🎉🎉 I will join National University of Singapore (NUS) for my Ph.D. journey, starting Aug. 2025.
- *2024.12*: &nbsp;🎉🎉 We release [**AntiLeak-Bench**](https://arxiv.org/pdf/2412.13670), an automated anti-leakage LLM benchmarking framework.
- *2024.12*: &nbsp;🎉🎉 We release [**RuleArena**](https://arxiv.org/pdf/2412.08972), an LLM rule-guided reasoning benchmark.

# 📝 Publications

<!-- <div class='paper-box-text' markdown="1">

**<font color="navy">Measuring and Mitigating Rapport Bias of Large Language Models under Multi-Agent Social Interactions</font>**

Maojia Song, Tej Deep Pala, **Ruiwen Zhou**, Weisheng Jin, Amir Zadeh, Chuan Li, Dorien Herremans, Soujanya Poria

***arXiv preprint*** &nbsp; \[ [Paper](https://arxiv.org/pdf/2508.18321) | [Code]() \]
</div>

<br> -->

<div class='paper-box-text' markdown="1">

**<font color="navy">RuleArena: A Benchmark for Rule-Guided Reasoning with LLMs in Real-World Scenarios</font>**

**Ruiwen Zhou**, Wenyue Hua, Liangming Pan, Sitao Cheng, Xiaobao Wu, En Yu, William Yang Wang

***ACL 2025*** &nbsp; \[ [Paper](https://arxiv.org/pdf/2412.08972) | [Code](https://github.com/skyriver-2000/RuleArena) \]
</div>

<br>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 2024</div><img src='images/rulearena.png' alt="sym" width="100%"></div></div> -->
<div class='paper-box-text' markdown="1">

**<font color="navy">AntiLeak-Bench: Preventing Data Contamination by Automatically Constructing Benchmarks with Updated Real-World Knowledge</font>**

Xiaobao Wu, Liangming Pan, Yuxi Xie, **Ruiwen Zhou**, Shuai Zhao, Yubo Ma, Mingzhe Du, Rui Mao, Shuai Zhao, Anh Tuan Luu, William Yang Wang

***ACL 2025 (Oral)*** &nbsp; \[ [Paper](https://arxiv.org/pdf/2412.13670) | [Code](https://github.com/bobxwu/antileak-bench) \]
</div>

<br>

<div class='paper-box-text' markdown="1">

**<font color="navy">TRAD: Enhancing LLM Agents with Step-Wise Thought Retrieval and Aligned Decision</font>**

**Ruiwen Zhou**, Yingxuan Yang, Muning Wen, Ying Wen, Wenhao Wang, Chunling Xi, Guoqiang Xu, Yong Yu, Weinan Zhang

***SIGIR 2024*** &nbsp; \[ [Paper](https://arxiv.org/pdf/2403.06221) | [Code](https://github.com/skyriver-2000/TRAD-Official) \]
</div>
<!-- </div> -->

<br>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv preprint</div><img src='images/rulearena.png' alt="sym" width="100%"></div></div> -->
<div class='paper-box-text' markdown="1">

**<font color="navy">Is Risk-Sensitive Reinforcement Learning Properly Resolved?</font>**

**Ruiwen Zhou**, Minghuan Liu, Kan Ren, Xufang Luo, Weinan Zhang, Dongsheng Li

***DAI 2025*** &nbsp; \[ [Paper](https://arxiv.org/pdf/2307.00547) \]
</div>
<!-- </div> -->

<br>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2022</div><img src='images/rulearena.png' alt="sym" width="100%"></div></div> -->
<div class='paper-box-text' markdown="1">

**<font color="navy">Learning Enhanced Representations for Tabular Data via Neighborhood Propagation</font>**

Kounianhua Du, Weinan Zhang, **Ruiwen Zhou**, Yangkun Wang, Xilong Zhao, Jiarui Jin, Quan Gan, Zheng Zhang, David Wipf

***NeurIPS 2022*** &nbsp; \[ [Paper](https://arxiv.org/pdf/2206.06587) | [Code](https://github.com/KounianhuaDu/PET) \]
</div>
<!-- </div> -->

<br>

# 🎖 Honors and Awards
- *2025.08* &nbsp;&nbsp; NUS Research Scholarship.
- *2024.11* &nbsp;&nbsp; Huatai Securities Scholarship (~Top 10% out of 179).
- *2024.11* &nbsp;&nbsp; First-Class Excellence Scholarship (Top 30% out of 179).
- *2022.11* &nbsp;&nbsp; First-Class Excellence Scholarship (Top 30% out of 179).
- *2021.12* &nbsp;&nbsp; B-Class Excellence Scholarship (Top 10% out of 144).
- *2021.12* &nbsp;&nbsp; Zhiyuan Honors Scholarship (Top 5% students in Zhiyuan Honors Program).
- *2021.04* &nbsp;&nbsp; Outstanding Winner of MCM/ICM 2021 (~Top 0.15% among the world).
- *2020.12* &nbsp;&nbsp; **A-Class Excellence Scholarship (Top 1 out of 144)**.
- *2020.12* &nbsp;&nbsp; **National Scholarship (Top 2 out of 144)**.
- *2020.12* &nbsp;&nbsp; Zhiyuan Honors Scholarship (Top 5% students in Zhiyuan Honors Program).
- *2019.11* &nbsp;&nbsp; B-Class Excellence Scholarship (Top 10% out of 144).
- *2019.11* &nbsp;&nbsp; Zhiyuan Honors Scholarship (Top 5% students in Zhiyuan Honors Program).

# 📖 Educations
- *2025.08 - Present*, Ph.D. in Computer Science, NUS.
- *2022.09 - 2025.03*, M.Eng. in Computer Science and Technology, SJTU.
- *2018.09 - 2022.06*, B.Eng. in Information Engineering, SJTU.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
<!-- - *2025.04 - 2025.08*, Shanghai AI Lab, *Advised by: [Jie Fu](https://bigaidream.github.io/)*. -->
- *2024.07 - 2024.12*, UCSB NLP Group, *Advised by: [Prof. William Yang Wang](https://sites.cs.ucsb.edu/~william)*.
- *2022.02 - 2023.02*, Amazon Web Service, *Advised by: [Quan Gan](https://www.amazon.science/author/quan-gan)*.
- *2021.08 - 2022.01*, Microsoft Research Asia, *Advised by: [Kan Ren](https://www.saying.ren/)*.

# 👀 Miscellaneous
In my spare time, I love:
- **Stroll:** I often go for a walk to beautiful sites nearby and recover my energy.
- **Music:** I listen to pop. songs, musicals, symphonies, etc. I also play the piano and sing.
- **Sports:** I watch NBA, F1, etc. games. I am a fan of James Harden and Lewis Hamilton.

<div style="padding-top: 100px; transform: scale(0.5); transform-origin: top center;">
    <script style="width:50%" type="text/javascript" id="clustrmaps" src="//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=a&t=tt&d=pfXNheCGCTq2ev5ATlMo7sNGDhev4oUjVOF5WLbyZao"></script>
</div>
