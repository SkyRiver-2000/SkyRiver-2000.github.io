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

I am a third-year CS Master student at Shanghai Jiao Tong University (SJTU), advised by [Prof. Weinan Zhang](https://wnzhang.net). Previously, I obtained my Bachelor's degree in Inforamtion Engineering from SJTU in 2022.

Recently, my research works mainly focus on:
* Evaluation and analysis of LLMs.
* LLM with retrieval augmentation.
* LLM reasoning, planning, and rule-following.
* Interactive LLM agents.

Feel free to reach out if you are interested in my research or want to discuss with me.

# 🔥 News
- *2024.12*: &nbsp;🎉🎉 We release [**AntiLeak-Bench**](https://arxiv.org/pdf/2412.13670), an automated anti-leakage LLM benchmarking framework.
- *2024.12*: &nbsp;🎉🎉 We release [**RuleArena**](https://arxiv.org/pdf/2412.08972), an LLM rule-guided reasoning benchmark.
- *2024.11*: &nbsp;🎉🎉 I will attend SoCal NLP 2024. Hope to see you there.
- *2024.07*: &nbsp;🎉🎉 I will serve as a volunteer host for SIGIR 2024 AgentIR Workshop. Hope to see you there.
- *2024.07*: &nbsp;🎉🎉 I will present our work [**TRAD**](https://arxiv.org/pdf/2403.06221) at SIGIR 2024 in Washington D.C.
- *2024.07*: &nbsp;🎉🎉 I start my 6-month visit at UCSB NLP Group.
- *2024.03*: &nbsp;🎉🎉 One paper [**TRAD**](https://arxiv.org/pdf/2403.06221) is accepted by **SIGIR 2024**.
- *2024.03*: &nbsp;🎉🎉 We release a retrieval-augmented LLM agent framework [**TRAD**](https://arxiv.org/pdf/2403.06221).

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv preprint</div><img src='images/rulearena.png' alt="sym" width="100%"></div></div> -->
<div class='paper-box-text' markdown="1">
**[arXiv preprint]** [RuleArena: A Benchmark for Rule-Guided Reasoning with LLMs in Real-World Scenarios](https://arxiv.org/pdf/2412.08972)

**Ruiwen Zhou**, Wenyue Hua, Liangming Pan, Sitao Cheng, Xiaobao Wu, En Yu, William Yang Wang

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We create the <strong>RuleArena</strong> benchmark for LLM rule-guided reasoning, with a comprehensive set of 95 policies/rules drawn from real-world scenarios and 816 datapoints of different difficulty levels for LLM evaluation. We further propose a suite of evaluation metrics for both rule selection and rule application, providing fine-grained insights into LLM performances.
- Existing state-of-the-art LLMs, such as GPT-4o and Claude-3.5 Sonnet, mostly fail on complex rule-guided reasoning tasks from <strong>RuleArena</strong>. By examining common failure cases and identifying difficult rule types, we uncover several systematic issues that limit LLMs' rule-guided reasoning capabilities.
</div>
<!-- </div> -->

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 2024</div><img src='images/rulearena.png' alt="sym" width="100%"></div></div> -->
<div class='paper-box-text' markdown="1">

**[arXiv preprint]** [AntiLeak-Bench: Preventing Data Contamination by Automatically Constructing Benchmarks with Updated Real-World Knowledge](https://arxiv.org/pdf/2412.13670)

Xiaobao Wu, Liangming Pan, Yuxi Xie, **Ruiwen Zhou**, Shuai Zhao, Yubo Ma, Mingzhe Du, Rui Mao, Shuai Zhao, Anh Tuan Luu, William Yang Wang

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We create the <strong>AntiLeak-Bench</strong> framework, which collects samples with explicitly new knowledge absent from LLMs' training sets, and thus ensures strictly contamination-free evaluation. This building workflow is also automated for maintainance and update without human labor.
- Experiments show that pre-cutoff samples come with data contamination, which inflates LLMs' performance, while contamination-free post-cutoff samples collected by our <strong>AntiLeak-Bench</strong> are more challenging and can more accurately assess LLMs.
</div>

<div class='paper-box-text' markdown="1">

**[SIGIR 2024]** [TRAD: Enhancing LLM Agents with Step-Wise Thought Retrieval and Aligned Decision](https://arxiv.org/pdf/2403.06221)

**Ruiwen Zhou**, Yingxuan Yang, Muning Wen, Ying Wen, Wenhao Wang, Chunling Xi, Guoqiang Xu, Yong Yu, Weinan Zhang

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a novel retrieval-augmented LLM agent **TRAD**. It achieves step-wise relevant demonstration selection via **thought retrieval (TR)**, and applies an **aligned decision (AD)** module to augment LLM with temporal neighboring steps and their corresponding order information of retrieved demonstrations during action prediction.
- **TRAD** significantly outperforms existing SoTA LLM agents such as Synapse and ReAct on common LLM agent benchmarks like ALFWorld (householding) and Mind2Web (web navigation).
</div>
<!-- </div> -->

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv preprint</div><img src='images/rulearena.png' alt="sym" width="100%"></div></div> -->
<div class='paper-box-text' markdown="1">

**[arXiv preprint]** [Is Risk-Sensitive Reinforcement Learning Properly Resolved?](https://arxiv.org/pdf/2307.00547)

**Ruiwen Zhou**, Minghuan Liu, Kan Ren, Xufang Luo, Weinan Zhang, Dongsheng Li

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We reveal the improper optimization in existing distributional risk-sensitive RL (RSRL) algorithms, showing that maximizing distortion risk measure at every step in a dynamic programming style leads to divergence.
- To address this issue, we propose a novel RSRL algorithm **Trajectory Q-Learning (TQL)**. By incorporating history return distribution, **TQL** achieves theoretical optimality and outperforms existing methods in RSRL tasks.
</div>
<!-- </div> -->

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2022</div><img src='images/rulearena.png' alt="sym" width="100%"></div></div> -->
<div class='paper-box-text' markdown="1">

**[NeurIPS 2022]** [Learning Enhanced Representations for Tabular Data via Neighborhood Propagation](https://arxiv.org/pdf/2206.06587)

Kounianhua Du, Weinan Zhang, **Ruiwen Zhou**, Yangkun Wang, Xilong Zhao, Jiarui Jin, Quan Gan, Zheng Zhang, David Wipf

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a GNN-based tabular prediction model **PET**. It considers both row-wise (across sample) and column-wise (across feature) feature interaction by transforming each target sample with retrieved relevant sample into a hypergraph and conducting message passing on it.
- On a wide range of tabular prediction tasks like CTR prediction and top-<em>n</em> recommendation, **PET** surpasses SoTA methods by a large margin.
</div>
<!-- </div> -->

# 🎖 Honors and Awards
- *2024.11* Huatai Securities Scholarship (~Top 10% out of 179).
- *2024.11* First-Class Excellence Scholarship (Top 30% out of 179).
- *2022.11* First-Class Excellence Scholarship (Top 30% out of 179).
- *2021.12* B-Class Excellence Scholarship (Top 10% out of 144).
- *2021.12* Zhiyuan Honors Scholarship (Top 5% students in Zhiyuan Honors Program).
- *2021.04* Outstanding Winner of MCM/ICM 2021 (~Top 0.15% among the world).
- *2020.12* **A-Class Excellence Scholarship (Top 1 out of 144)**.
- *2020.12* **National Scholarship (Top 2 out of 144)**.
- *2020.12* Zhiyuan Honors Scholarship (Top 5% students in Zhiyuan Honors Program).
- *2019.11* B-Class Excellence Scholarship (Top 10% out of 144).
- *2019.11* Zhiyuan Honors Scholarship (Top 5% students in Zhiyuan Honors Program).

# 📖 Educations
- *2022.09 - 2025.03*, M.Eng. in Computer Science and Technology, SJTU.
- *2018.09 - 2022.06*, B.Eng. in Information Engineering, SJTU.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2024.07 - 2024.12*, UCSB NLP Group, *Advised by: [Prof. William Yang Wang](https://sites.cs.ucsb.edu/~william)*.
- *2022.02 - 2023.02*, Amazon Web Service, *Advised by: [Quan Gan](https://www.amazon.science/author/quan-gan)*.
- *2021.08 - 2022.01*, Microsoft Research Asia, *Advised by: [Kan Ren](https://www.saying.ren/)*.

# 👀 Miscellaneous
In my spare time, I love:
- **Stroll:** I often go for a walk to beautiful sites nearby and recover my energy.
- **Music:** I listen to pop. songs, musicals, symphonies, etc. I also play the piano and sing.
- **Sports:** I watch NBA, F1, etc. games. I am a fan of James Harden and Lewis Hamilton.

<div style="padding-top: 100px; transform: scale(0.5); transform-origin: top center;">
    <script style="width:50%" type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=pfXNheCGCTq2ev5ATlMo7sNGDhev4oUjVOF5WLbyZao&cl=ffffff&w=a"></script>
</div>
