---
title: 'DAUNT: Ensemble Disagreement as Actionable Uncertainty for Imbalanced Fraud
  Detection'
authors:
- Xinyao Liu
- Guixiang Zhu
date: '2026-08-01'
publishDate: '2026-11-04T07:40:26.134688Z'
publication_types:
- article-journal
publication: '*Multidisciplinary Digital Publishing Institute*'
doi: 10.3390/make8080233
abstract: 'Detecting a few hundred fraudulent transactions among hundreds of thousands
  is an extreme class-imbalance problem where one miss can cost a full transaction
  value. Stacking heterogeneous classifiers is the standard recipe, yet under a leakage-free,
  precision–recall evaluation, its ranking gain over the best single model is inconsistent:
  sizable when the base learners are diverse, and negligible when they are redundant.
  The ensemble’s dependable value lies elsewhere: member disagreement is a usable,
  threshold-free estimate of epistemic uncertainty. We propose Daunt (Disagreement
  As UNcertainty for Triage), which turns this disagreement into three deployment
  layers over one ensemble: (i) routing the most uncertain transactions to human review
  by ranking them on base-learner disagreement, (ii) deciding alarms by an example-dependent
  rule that weighs the fraud score against the transaction amount, and (iii) attaching
  interpretations verified for faithfulness and stability. On two contrasting datasets,
  the anonymized ULB (0.17% fraud) and feature-rich IEEE-CIS (3.5% fraud), deferring
  the 5% most uncertain transactions raises system recall from 0.76 to 0.91 (ULB)
  and 0.66 to 0.75 (IEEE-CIS) while removing every automated false alarm, and the
  example-dependent rule recovers more fraudulent money than any global threshold.
  Daunt reframes the heterogeneous ensemble as a source of actionable uncertainty
  rather than an end in itself.'
tags:
- class imbalance
- cost-sensitive learning
- ensemble disagreement
- fraud detection
- interpretability
- selective prediction
- uncertainty quantification
links:
- name: URL
  url: https://www.mdpi.com/2504-4990/8/8/233
---
