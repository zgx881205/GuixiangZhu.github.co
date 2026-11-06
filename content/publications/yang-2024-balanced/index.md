---
title: "Balanced Influence Maximization in Social Networks Based on Deep Reinforcement Learning"
authors:
  - Shuxin Yang
  - Quanming Du
  - Guixiang Zhu
  - Jie Cao
  - Lei Chen
  - Weiping Qin
  - Youquan Wang
date: "2024-01-01"
publication_types:
  - article-journal
doi: "10.1016/j.neunet.2023.10.030"
publication:
  name: "Neural Networks"
  volume: "169"
  pages: "334-351"
abstract: >-
  Balanced influence maximization aims to balance the influence maximization of multiple different entities in social networks and avoid the emergence of filter bubbles and echo chambers. Recently, an increasing number of studies have drawn attention to the study of balanced influence maximization in social networks and achieves success to some extent. However, most of them still have two major shortcomings. First, the previous works mainly focus on spreading the influence of multiple target entities to more users, ignoring the potential influence of the correlation between the target entities and other entities on information propagation in real social networks. Second, the existing methods require a large amount of diffusion sampling for influence estimation, making it difficult to apply to large social networks. To this end, we propose a Balanced Influence Maximization framework based on Deep Reinforcement Learning named BIM-DRL, which consists of two core components: an entity correlation evaluation module and a balanced seed node selection module. Specifically, in the entity correlation evaluation module, an entity correlation evaluation model based on the users' historical behavior sequences is proposed, which can accurately evaluate the impact of entity correlation on information propagation. In the balanced seed node selection module, a balanced influence maximization model based on deep reinforcement learning is designed to train the parameters in the objective function, and then a set of seed nodes that maximize the balanced influence is found. Extensive experiments on six real-life network datasets demonstrate the superiority of BIM-DRL over state-of-the-art methods on the metrics of balanced influence spread and balanced propagation accuracy.
tags:
  - Balanced influence maximization
  - Deep reinforcement learning
  - Entity correlation evaluation
  - Social network analysis
featured: true
links:
  - name: URL
    url: "https://www.sciencedirect.com/science/article/pii/S0893608023005841"
---