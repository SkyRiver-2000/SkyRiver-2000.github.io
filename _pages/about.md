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

I am a 2nd-year CS Ph.D. student at National University of Singapore (NUS), supervised by [Prof. Min-Yen Kan](https://www.comp.nus.edu.sg/~kanmy/) and [Prof. Soujanya Poria](https://soujanyaporia.github.io/). Previously, I obtained my Master's degree in Computer Science and Bachelor's degree in Information Engineering from Shanghai Jiao Tong University (SJTU), fortunately advised by [Prof. Weinan Zhang](https://wnzhang.net). I also work closely with [Dr. Wenyue Hua](https://wenyueh.github.io/en/), [Prof. Liangming Pan](http://liangmingpan.bio/), and [Prof. Muning Wen](https://morning9393.github.io/).

Recently, my research mainly focus on LLM reasoning and AI agents, especially:
* LLM mid-training and post-training.
* LLM memory management and augmentation.
* LLM-based multi-agent systems.

Feel free to reach out to me if you are interested in academic discussion / collaboration.

<!-- **I am looking for 2026 summer research internship globally!** Feel free to reach out to me if there is an opportunity that you believe I am a good fit, or you are interested in academic discussion / collaboration. -->

# 🔥 News
- *2026.01*: &nbsp;🎉🎉 One paper [**KAIROS**](https://arxiv.org/pdf/2508.18321) is accepted by **ICLR 2026**.
- *2026.01*: &nbsp;🎉🎉 I will attend AAAI 2026 at Singapore during Jan 22-27, 2026. Let's connect!
- *2025.10*: &nbsp;🎉🎉 I will attend EMNLP 2025 at Suzhou during Nov 5-7, 2025. Let's connect!
- *2025.07*: &nbsp;🎉🎉 [**AntiLeak-Bench**](https://arxiv.org/pdf/2412.13670) is selected as SAC Highlight at ACL 2025!
- *2025.06*: &nbsp;🎉🎉 I will present our work [**RuleArena**](https://arxiv.org/pdf/2412.08972) and [**AntiLeak-Bench**](https://arxiv.org/pdf/2412.13670) at ACL 2025 in Vienna, Austria.
- *2025.05*: &nbsp;🎉🎉 Two papers [**RuleArena**](https://arxiv.org/pdf/2412.08972) and [**AntiLeak-Bench**](https://arxiv.org/pdf/2412.13670) are accepted by **ACL 2025 (Main)**.
- *2025.04*: &nbsp;🎉🎉 I will present our work [**RuleArena**](https://arxiv.org/pdf/2412.08972) at ICLR 2025 Workshops (Reason&Plan, SCI-FM). Hope to see you there.
- *2025.04*: &nbsp;🎉🎉 I will join National University of Singapore (NUS) for my Ph.D. journey, starting Aug. 2025.

# 📝 Selected Publications

<div class='paper-box-text' markdown="1" style="padding-top: 10px;">

**<font color="navy">MemQ: Integrating Q-Learning into Self-Evolving Memory Agents over Provenance DAGs</font>**

Junwei Liao, Haoting Shi, **Ruiwen Zhou**, Jiaqian Wang, Shengtao Zhang, Wei Zhang, Weinan Zhang, Ying Wen, Zhiyu Li, Feiyu Xiong, Bo Tang, Muning Wen

***arXiv preprint*** &nbsp; \[ [Paper](https://arxiv.org/abs/2605.08374) | [Code](https://github.com/jwliao-ai/MemQ) \]
</div>

<br>

<div class='paper-box-text' markdown="1" style="padding-top: 10px;">

**<font color="navy">Epistemic Context Learning: Building Trust the Right Way in LLM-Based Multi-Agent Systems</font>**

**Ruiwen Zhou**<superscript>*</superscript>, Maojia Song<superscript>*</superscript>, Xiaobao Wu, Sitao Cheng, Xunjian Yin, Yuxi Xie, Zoey Hao, Wenyue Hua, Liangming Pan, Soujanya Poria, Min-Yen Kan

***arXiv preprint*** &nbsp; \[ [Paper](https://arxiv.org/pdf/2601.21742) | [Code](https://github.com/skyriver-2000/epistemic-context-learning) \]
</div>

<br>

<div class='paper-box-text' markdown="1" style="padding-top: 10px;">

**<font color="navy">MemRL: Self-Evolving Agents via Runtime Reinforcement Learning on Episodic Memory</font>**

Shengtao Zhang<superscript>*</superscript>, Jiaqian Wang<superscript>*</superscript>, **Ruiwen Zhou**, Junwei Liao, Yuchen Feng, Weinan Zhang, Ying Wen, Zhiyu Li, Feiyu Xiong, Yutao Qi, Bo Tang, Muning Wen

***arXiv preprint*** &nbsp; \[ [Paper](https://arxiv.org/pdf/2601.03192) | [Code]() \]
</div>

<br>

<div class='paper-box-text' markdown="1" style="padding-top: 10px;">

**<font color="navy">From Atomic to Composite: Reinforcement Learning Enables Generalization in Complementary Reasoning</font>**

Sitao Cheng, Xunjian Yin, **Ruiwen Zhou**, Yuxuan Li, Xinyi Wang, Liangming Pan, William Yang Wang, Victor Zhong

***arXiv preprint*** &nbsp; \[ [Paper](https://arxiv.org/pdf/2512.01970) | [Code](https://github.com/sitaocheng/from_atomic_to_composite) \]
</div>

<br>

<div class='paper-box-text' markdown="1">

**<font color="navy">Measuring and Mitigating Rapport Bias of Large Language Models under Multi-Agent Social Interactions</font>**

Maojia Song, Tej Deep Pala, **Ruiwen Zhou**, Weisheng Jin, Amir Zadeh, Chuan Li, Dorien Herremans, Soujanya Poria

***ICLR 2026*** &nbsp; \[ [Paper](https://arxiv.org/pdf/2508.18321) | [Code](https://github.com/declare-lab/KAIROS) \]
</div>

<br>

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

***ACL 2025 (Oral) | 🏆 SAC Highlight*** &nbsp; \[ [Paper](https://arxiv.org/pdf/2412.13670) | [Code](https://github.com/bobxwu/antileak-bench) \]
</div>

<br>

<div class='paper-box-text' markdown="1">

**<font color="navy">TRAD: Enhancing LLM Agents with Step-Wise Thought Retrieval and Aligned Decision</font>**

**Ruiwen Zhou**, Yingxuan Yang, Muning Wen, Ying Wen, Wenhao Wang, Chunling Xi, Guoqiang Xu, Yong Yu, Weinan Zhang

***SIGIR 2024*** &nbsp; \[ [Paper](https://arxiv.org/pdf/2403.06221) | [Code](https://github.com/skyriver-2000/TRAD-Official) \]
</div>
<!-- </div> -->

<br>

# 🎖 Honors and Awards
- *2025.08* &nbsp;&nbsp; NUS Research Scholarship.
- *2024.11* &nbsp;&nbsp; Huatai Securities Scholarship (~Top 10% out of 179).
- *2021.04* &nbsp;&nbsp; Outstanding Winner of MCM/ICM 2021 (~Top 0.15% among the world).
- *2020.12* &nbsp;&nbsp; **National Scholarship (Top 1 out of 144)**.

# 📖 Educations
- *2025.08 - Present*, Ph.D. in Computer Science, NUS.
- *2022.09 - 2025.03*, M.Eng. in Computer Science and Technology, SJTU.
- *2018.09 - 2022.06*, B.Eng. in Information Engineering, SJTU.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2026.04 - Present*, MiniMax (Top Talent Intern).
- *2024.07 - 2024.12*, UCSB NLP Group, *Advised by: [Prof. William Yang Wang](https://sites.cs.ucsb.edu/~william)*.
- *2022.02 - 2023.02*, Amazon Web Service, *Mentored by: [Quan Gan](https://linkedin.com/in/quan-gan-231992136)*.
- *2021.08 - 2022.01*, Microsoft Research Asia, *Mentored by: [Kan Ren](https://www.saying.ren/)*.

# ✉️ Academic Services

- **Reviewer:** ICML (2026), NeurIPS (2026), ARR (2026), TPAMI.
- **Volunteer:** SIGIR (2024, Co-Hosting the GenIR Workshop)

# 👀 Miscellaneous
In my spare time, I love:
- **Joggling:** I often go for a walk to beautiful sites nearby and recover my energy.
- **Music:** I listen to pop. songs, musicals, symphonies, etc. I also play the piano and sing.
- **Sports:** I watch NBA, F1, etc. games. I am a fan of James Harden and Lewis Hamilton.

<!-- <div style="padding-top: 100px; transform: scale(0.5); transform-origin: top center;">
    <script style="width:50%" type="text/javascript" id="clustrmaps" src="//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=a&t=tt&d=pfXNheCGCTq2ev5ATlMo7sNGDhev4oUjVOF5WLbyZao"></script>
</div> -->