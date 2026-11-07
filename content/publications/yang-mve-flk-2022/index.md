---
title: 'MVE-FLK: A multi-task legal judgment prediction via multi-view encoder fusing
  legal keywords'
authors:
- Shuxin Yang
- Suxin Tong
- Guixiang Zhu
- Jie Cao
- Youquan Wang
- Zhengfa Xue
- Hongliang Sun
- Yu Wen
date: '2022-03-01'
publishDate: '2026-11-07T03:27:41.043980Z'
publication_types:
- article-journal
doi: 10.1016/j.knosys.2021.107960
abstract: Legal Judgment Prediction (LJP) aims to predict the judgment result based
  on the fact description of a criminal case, and is gradually becoming a hot research
  topic in the legal realm. Generally, a classic LJP contains three subtasks, i.e.,
  applicable law article prediction, charge prediction, and term of penalty prediction.
  In real-world scenarios, both charge prediction and applicable law article prediction
  are actually the tasks of multi-class classification with multi-label learning.
  However, most existing studies model them as the problems of multi-class classification
  with single-label learning. Besides, they only consider the context of the fact
  description, and ignore the exploitation of effective keywords that are widely existed
  in abundant law articles. To fill the above gaps, we propose a novel multi-task
  legal judgment prediction framework via multi-view encoder fusing legal keywords,
  named MVE-FLK, to jointly model multiple subtasks in LJP. Specifically, the multi-view
  encoder is the core module of MVE-FLK, in this module, we devise a word and sentence
  encoder (WSE) with an attention mechanism to fuse legal keywords. And then, we develop
  a multi-view attention network to combine WSE with classic Transformer and DAN (Deep
  Averaging Network) for encoding the case from multiple views. After that, we propose
  a multi-task prediction module by developing a novel keywords fusing approach to
  enhance the performance of multi-task prediction. In addition, we devise a unique
  prediction principle for each subtask at a fine-grained level, which effectively
  improves the performance of subtasks. The experimental results on two real-life
  legal datasets show that our model yields significant prediction performance advantages
  over six competitive methods.
tags:
- Legal judgment prediction 
- Multi-class classification 
- Multi-label learning 
- Multi-task learning 
- Word and sentence encoder
links:
- name: URL
  url: https://linkinghub.elsevier.com/retrieve/pii/S095070512101090X
---
