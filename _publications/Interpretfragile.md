---
title: "Interpretable but Fragile? Robustness of Concept Bottlenecks under Geometric-Semantic Perturbations"
collection: publications
permalink: /publication/Interpretfragile
excerpt: 'This paper provides a framework to analyze the robustness of concept-based models.'
date: 2026-9-26
venue: 'NeurIPS 2026'
paperurl: ''
citation: 'accepted by neurips.'
---

Concept Bottleneck Models (CBMs) are designed to provide interpretable intermediate representations, yet how such bottlenecks affect robustness remains unclear, with existing studies reporting mixed and sometimes contradictory findings. We argue that these discrepancies arise from conflating different robustness notions and perturbation regimes, rather than from fundamental disagreements about CBMs themselves.
To disentangle these factors, we introduce a generator-based evaluation framework that enables controlled comparisons between standard classifiers and CBMs  under two distinct perturbation types: continuous geometric perturbations in latent space and discrete semantic interventions in concept space. We further evaluate a prototype-based interpretable model, PixPNet, showing that the same perturbation-to-prediction evaluation and certification pipeline extends beyond concept bottlenecks without requiring alignment between heterogeneous internal representations.
Within this framework, we evaluate robustness both empirically, via prediction and concept-level sensitivity metrics, and certifiably, using randomized smoothing in latent and concept spaces. 
Across experiments on CUB and RIVAL10 variants, we reconcile previously conflicting findings by clarifying when, and in what sense, concept bottlenecks do or do not improve robustness. By further analyzing robustness under varying task conditions, including class semantic similarity and concept vocabulary size, we show that interpretability does not inherently confer robustness. Instead, concept bottlenecks shift where and how sensitivity manifests, revealing a nuanced interpretability robustness trade off that depends critically on the perturbation regime and task structure.
Together, our results show that interpretability and robustness are distinct objectives: interpretable intermediate representations do not uniformly improve robustness, but instead redistribute sensitivity across perturbation spaces and model families.
