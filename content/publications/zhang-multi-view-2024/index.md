---
title: Multi-view Contrastive Learning for Next POI Recommendation
authors:
- Jin Zhang
- Guixiang Zhu
- Yihan Chen
- Yiheng Lu
- Xinyi Wang
- Shi Feng
date: '2024-11-15'
publishDate: '2026-11-08T04:10:36.080089Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 2024 8th International Conference on Computing and
  Data Analysis*'
doi: 10.1145/3705374.3705385
abstract: Next POI recommendation aims to forecast their subsequent locations, which
  base been an important applications for LocationBased Services (LBS). Recently,
  there has been a growing interest in the investigation of POI recommendation using
  various deep learning techniques, and achieved great success. However, most of them
  only model the users preferences from a single view, such as the graph-structured
  features in the trajectory that indicate the preferences of individuals, or the
  dynamic change of personal preferences from trajectory sequences. Moreover, they
  ignore leverage the unique self-supervised signals to guide those two views of user
  preferences leaning perform better. To fill these critical voids, this paper proposes
  a Multi-View Contrastive Learning for next POI recommendation named MVCL-POI. Specifically,
  MVCL-POI first exploits dynamic-aware GCN from trajectory graph to automatically
  extract graph-structured features with considerations of rich node connections.
  After that, MVCL-POI utilizes a temporal-aware transformer to capture users’ dynamic
  interest from their historical trajectory sequences. Finally, a multi-view contrastive
  learning is designed to maximize the agreement between two views of users’ representations.
  Experiments results on two real-life LBSN datasets show that MVCL-POI yields significant
  performance advantages over the competitive next POI recommendation methods.
tags:
- /unread
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3705374.3705385
---
