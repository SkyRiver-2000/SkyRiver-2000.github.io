---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* I am now pursuing **Bachelor's Degree** in Shanghai Jiao Tong University, advised by Prof. [Weinan Zhang](https://wnzhang.net).

Experience
======
* 2019.10-2021.01: Research Assistant
  * Data Communication and Engineering (DCE) lab
  * Topic: Spatial crowdsourcing
  * Advisor: Prof. [Xiaofeng Gao](https://www.cs.sjtu.edu.cn/~gao-xf/)

* 2021.01-present: Research Assistant
  * APEX Data & Knowledge Management lab
  * Topic: Imitation learning, Model-based RL
  * Advisor: Prof. [Weinan Zhang](https://wnzhang.net)
  
Skills
======
* Theory of statistical machine learning
* Python programming and mainstream machine learning package
  * Deep learning: PyTorch, Keras
  * Machine learning: scikit-learn
  * Data analysis: Numpy, Pandas, Scipy
* Some other programming languages: C/C++, MATLAB
* Academic writing using LaTeX, Origin, etc.

Projects
======
### 2021.05-2021.06: Data Mining and Predicting on AceMap
This is the final project for course *EE226*, *Big Data Mining (AI)*, in SJTU. We are required to conduct node classification and link prediction tasks on an academic citation network called AceMap. Our group proposed simple and effective solutions and achieve strong performance on Kaggle competitions.

**Our code:** [click here](https://github.com/SkyRiver-2000/EE226-Final-Project) to visit our GitHub repository  
**Our paper:** [click here](../files/EE226-report.pdf) for our complete paper

### 2020.05-2020.06: Imitation Learning for Control in 2048 Games
This is the final project for course *EE228*, *Machine Learning (AI)*, in SJTU. We are required to train an agent with supervisions from the Expectimax, a powerful planning based agent, to achieve high scores in an 2048 game. I combine two convolution architectures into a novel one, fine tune the parameters, and obtain one of the most powerful agent in the class.

**My code:** [click here](https://github.com/SkyRiver-2000/EE228-Final-Assignment) to visit my GitHub repository
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Refer to my formal CV at [here](../files/CV.pdf)
