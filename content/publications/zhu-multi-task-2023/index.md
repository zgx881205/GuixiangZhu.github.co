---
title: A Multi-Task Graph Neural Network with Variational Graph Auto-Encoders for
  Session-Based Travel Packages Recommendation
authors:
- Guixiang Zhu
- Jie Cao
- Lei Chen
- Youquan Wang
- Zhan Bu
- Shuxin Yang
- Jianqing Wu
- Zhiping Wang
date: '2023-05-24'
publishDate: '2026-11-04T07:40:25.943281Z'
publication_types:
- article-journal
doi: 10.1145/3577032
abstract: 'Session-based travel packages recommendation aims to predict users’ next
  click based on their current and historical sessions recorded by Online Travel Agencies
  (OTAs). Recently, an increasing number of studies attempted to apply Graph Neural
  Networks (GNNs) to the session-based recommendation and obtained promising results.
  However, most of them do not take full advantage of the explicit latent structure
  from attributes of items, making learned representations of items less effective
  and difficult to interpret. Moreover, they only combine historical sessions (long-term
  preferences) with a current session (short-term preference) to learn a unified representation
  of users, ignoring the effects of historical sessions for the current session. To
  this end, this article proposes a novel session-based model named STR-VGAE, which
  fills subtasks of the travel packages recommendation and variational graph auto-encoders
  simultaneously. STR-VGAE mainly consists of three components: travel packages encoder,
  users behaviors encoder, and interaction modeling. Specifically, the travel packages
  encoder module is used to learn a unified travel package representation from co-occurrence
  attribute graphs by using multi-view variational graph auto-encoders and a multi-view
  attention network. The users behaviors encoder module is used to encode user’ historical
  and current sessions with a personalized GNN, which considers the effects of historical
  sessions on the current session, and coalesce these two kinds of session representations
  to learn the high-quality users’ representations by exploiting a gated fusion approach.
  The interaction modeling module is used to calculate recommendation scores over
  all candidate travel packages. Extensive experiments on a real-life tourism e-commerce
  dataset from China show that STR-VGAE yields significant performance advantages
  over several competitive methods, meanwhile provides an interpretation for the generated
  recommendation list.'
tags:
- /unread
- auto-encoder
- graph mining
- multi-task learning
- session-based recommendation
- Travel recommendation
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3577032
---
