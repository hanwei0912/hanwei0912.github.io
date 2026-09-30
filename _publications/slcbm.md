---
title: "SL-CBM: Enhancing Concept Bottleneck Models with Semantic Locality for Better Interpretability"
collection: publications
permalink: /publication/slcbm
excerpt: 'This paper is about how to make concept bottleneck models have better semantic localization of the concepts.'
date: 2026-1-26
venue: 'AAAI 2026'
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/download/41147/45108'
citation: 'Zhang, H., Cheng, L., Wen, R., Zhang, Y., Zhang, L., & Hermanns, H. (2026, March). Sl-cbm: Enhancing concept bottleneck models with semantic locality for better interpretability. In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 40, No. 44, pp. 38093-38101).'
---

Explainable AI (XAI) is crucial for building transparent and trustworthy machine learning systems, especially in high-stakes domains. Concept Bottleneck Models (CBMs) have emerged as a promising ante-hoc approach that provides interpretable, concept-level explanations by explicitly modeling human-understandable concepts. However, existing CBMs often suffer from poor locality faithfulness, failing to spatially align concepts with meaningful image regions, which limits their interpretability and reliability. In this work, we propose SL-CBM (CBM with Semantic Locality), a novel extension that enforces locality faithfulness by generating spatially coherent saliency maps at both concept and class levels. SL-CBM integrates a  convolutional layer with a cross-attention mechanism to enhance alignment between concepts, image regions, and final predictions. Unlike prior methods, SL-CBM produces faithful saliency maps inherently tied to the model’s internal reasoning, facilitating more effective debugging and intervention. Extensive experiments on image datasets demonstrate that SL-CBM substantially improves locality faithfulness, explanation quality, and intervention efficacy while maintaining competitive classification accuracy. Our ablation studies highlight the importance of contrastive and entropy-based regularization for balancing accuracy, sparsity, and faithfulness. Overall, SL-CBM bridges the gap between concept-based reasoning and spatial explainability, setting a new standard for interpretable and trustworthy concept-based models. Our implementation is open-source and can be found at \url{https://github.com/Uzukidd/sl-cbm}.
[paper](https://ojs.aaai.org/index.php/AAAI/article/download/41147/45108)
