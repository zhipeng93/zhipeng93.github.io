---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Conference papers
======

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
- **Zhipeng Zhang**, Wentao Wu, Jiawei Jiang, Lele Yu, Bin Cui, Ce Zhang. ColumnSGD: A Column-oriented Framework for Distributed Stochastic Gradient Descent [ICDE 2020, **CCF-A**]
- **Zhipeng Zhang**, Bin Cui, Yingxia Shao, Lele Yu, Jiawei Jiang, Xupeng Miao. PS2: Parameter Server on Spark [SIGMOD 2019, **CCF-A**] 
- **Zhipeng Zhang**, Jiawei Jiang, Wentao Wu, Ce Zhang, Lele Yu, Bin Cui. MLlib*: Fast Training of GLMs using Spark MLlib [ICDE 2019, **CCF-A**] 
- **Zhipeng Zhang**, Yingxia Shao, Bin Cui, Ce Zhang. An Experimental Evaluation of SimRank-based Similarity Search Algorithms [VLDB 2017, **CCF-A**]
- **Zhipeng Zhang**, Jiawei Jiang, Lele Yu, Bin Cui. Angel+: A Large-Scale Machine Learning Platform on Angel. [Frontiers of Data and Computing, 2019]
- Jiawei Jiang, Pin Xiao, Lele Yu, Xiaosen Li, Jiefeng Cheng, Xupeng Miao, **Zhipeng Zhang**, Bin Cui. PSGraph: How Tencent trains extremely large-scale graphs with Spark? [ICDE 2020, **CCF-A**]
- Xiaoru Qu, Zhao Li, Jialin Wang, **Zhipeng Zhang**, …, Jun Gao. Category-aware Graph Neural Networks for Improving E-commerce Review Helpfulness Prediction. [CIKM 2020, **CCF-B**]
- Xinyi Zhang, **Zhipeng Zhang**, Bin Cui. An Reinforcement Learning-based Method for Join Optimization. [NDBC 2020，**CCF-C, Best Student Paper**] 
- Jiawei Jiang, **Zhipeng Zhang**, Bin Cui, Yunhai Tong, Ning Xu. StroMAX: Partitioning-based Scheduler for Real-time Stream Processing System [DASFAA 2017, **CCF-B**] 
- Shuyang Shi, **Zhipeng Zhang**, Bin Cui. Resume Activeness Prediction in Online Recruitment Scenarios [NDBC 2017, **CCF-C**]

Journal papers
======
- Yunyan Guo, **Zhipeng Zhang**, Wentao Wu, Jiawei Jiang, Ce zhang, Bin Cui, Jianzhong Li. Model Averaging in Distributed Machine Learning: A Case Study with Apache Spark [VLDBJ 2021, **CCF-A**]
- Wentao Zhang, Bin Yuan, **Zhipeng Zhang**, Bin Cui. Distributed Optimization and Implementation of Graph Embedding Algorithms. [JOS 2021, **CCF-A**]
- Xinyi Zhang, **Zhipeng Zhang**, Bin Cui. An Reinforcement Learning-based Method for Join Optimization. [SCIENTIA SINICA Informationis 2020] 
- Shuyang Shi, **Zhipeng Zhang**, Bin Cui. Resume Activeness Prediction in Online Recruitment Scenarios [JCST 2017, **CCF-B**]
