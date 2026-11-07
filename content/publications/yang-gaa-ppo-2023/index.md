---
title: 'GAA-PPO: A novel graph adversarial attack method by incorporating proximal
  policy optimization'
authors:
- Shuxin Yang
- Xiaoyang Chang
- Guixiang Zhu
- Jie Cao
- Weiping Qin
- Youquan Wang
- Zhendong Wang
date: '2023-11-01'
publishDate: '2026-11-07T03:27:41.054976Z'
publication_types:
- article-journal
doi: 10.1016/j.neucom.2023.126707
abstract: 'The Graph Convolutional Network (GCN) has demonstrated impressive performance
  in processing graph structured data. However recent studies have revealed that GCN
  is vulnerable to adversarial attacks, where a small amount of data modification
  can significantly affect the performance of the GCN models. While most existing
  studies node injection attacks with graph reinforcement learning by considering
  gradient information, they still suffer from the problems that the step size of
  the policy gradient is difficult to determine, and the attack effect needs to be
  further improved. In light of the above issues, this paper proposes a Graph Adversarial
  Attack method by incorporating Proximal Policy Optimization named GAA-PPO, which
  fills subtasks of sequentially generating features and links for injected nodes
  without modifying existing nodes or edges. GAA-PPO comprises two main components:
  node injection attack network (actor network) and value prediction network (critic
  network). Specifically, the actor network leverages a node generator and an edge
  sampler to generate appropriate features and edges for the injected nodes. Notably,
  a novel edge sampler that incorporates Approximation Personalized Propagation of
  Neural Prediction (APPNP) is introduced to effectively propagate malicious features
  of the injected nodes. On the other hand, the critic network evaluates the performance
  of the perturbed graph at each stage. To enhance the stability of the algorithm,
  GAA-PPO employs the importance sampling technique of Proximal Policy Optimization
  (PPO) during the training process. Extensive experiments on three publicly benchmark
  datasets show that GAA-PPO yields significant performance advantages over the state-of-the-art
  method.'
tags:
- Graph neural network 
- Graph Convolutional Network 
- Adversarial attack 
- Reinforcement learning
links:
- name: URL
  url: https://linkinghub.elsevier.com/retrieve/pii/S0925231223008305
---
