---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}

<!-- &nbsp;  
* **2021.05-2021.06: Data Mining and Predicting on *AceMap***

This is the final project for course *EE226*, *Big Data Mining (AI)*, in SJTU. We are required to conduct node classification and link prediction tasks on an academic citation network called *AceMap*. My group proposes simple and effective solutions and achieves an outstanding performance.

**Codes:** [click here](https://github.com/SkyRiver-2000/EE226-Final-Project) to visit our GitHub repository  
**Paper:** [click here](../files/EE226-report.pdf) for our solution paper

&nbsp;  
* **2021.02-2021.05: MALib: A Parallel Framework for Population-based Multi-agent Reinforcement Learning**

MALib is a parallel framework of population-based learning nested with (multi-agent) reinforcement learning (RL) methods. I mainly focus on the implementation of some imitation learning metrics and algorithms, which have not been released yet (might come up soon).

**Codes:** [click here](https://github.com/sjtu-marl/malib) to visit our GitHub repository

&nbsp;  
* **2020.05-2020.06: Imitation Learning for Control in 2048 Games**

This is the final project for course *EE228*, *Machine Learning (AI)*, in SJTU. We are required to train an agent with supervisions from the Expectimax, a powerful planning based agent, to achieve high scores in an 2048 game. I combine two convolution architectures into a novel one, fine tune the parameters, and obtain one of the most powerful agent in the class.

**Codes:** [click here](https://github.com/SkyRiver-2000/EE228-Final-Assignment) to visit my GitHub repository

&nbsp;  
# Other Projects
&nbsp;  
* **2021.03-2021.06: Batch Recognition of Book Labels on Mobile Devices**

This is the final project for course *EE225*, *Intelligent Internet of Things*, in SJTU. We are required to build a real-time system to recognize the book labels and corresponding book numbers. We use a two-stage scheme: localize the book labels first, and then generate subfigures for optical character recognition (OCR).

Our localization model is based on [NanoDet](https://github.com/RangiLyu/nanodet) and our OCR is based on [Tesseract](https://github.com/tesseract-ocr/tesseract). For better computation speed, we implement an adapative multi-thread scheduling algorithm for OCR.

**Slides:** [click here](../files/EE225-project.pdf) for our presentation slides. -->
