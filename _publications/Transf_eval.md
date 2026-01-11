---
title: "Revisiting Transferable Adversarial Images: Systemization, Evaluation, and New Insights"
collection: publications
permalink: /publication/Transf_eval
excerpt: 'This paper is about systematized evaluation of transferable adversarial robustness on image classification.'
date: 2025-09-16
venue: 'IEEE Transactions on Pattern Analysis and Machine Intelligence'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/11164808/'
citation: 'Zhao, Z., Zhang, H., Li, R., Sicre, R., Amsaleg, L., Backes, M., ... & Shen, C. (2025). Revisiting Transferable Adversarial Images: Systemization, Evaluation, and New Insights. IEEE Transactions on Pattern Analysis and Machine Intelligence.'
---

Transferable adversarial images raise critical security concerns for computer vision systems in real-world, black-box attack scenarios. Although many transfer attacks have been proposed, existing research lacks a systematic and comprehensive evaluation. In this paper, we systemize transfer attacks into five categories around the general machine learning pipeline and provide the first comprehensive evaluation, with 23 representative attacks against 11 representative defenses, including the recent, transfer-oriented defense and the real-world Google Cloud Vision. In particular, we identify two main problems of existing evaluations: (1) for attack transferability, lack of intra-category analyses with fair hyperparameter settings, and (2) for attack stealthiness, lack of diverse measures. Our evaluation results validate that these problems have indeed caused misleading conclusions and missing points, and addressing them leads to new, consensus-challenging insights, such as (1) an early attack, DI, even outperforms all similar follow-up ones, (2) the state-of-the-art (white-box) defense, DiffPure, is even vulnerable to (black-box) transfer attacks, and (3) even under the same Lp constraint, different attacks yield dramatically different stealthiness results regarding diverse imperceptibility metrics, finer-grained measures, and a user study. We hope that our analyses will serve as guidance on properly evaluating transferable adversarial images and advance the design of attacks and defenses.

[paper](https://ieeexplore.ieee.org/abstract/document/11164808/)
[code](https://github.com/ZhengyuZhao/TransferAttackEval)
