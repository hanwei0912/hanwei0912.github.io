---
title: "Opti-CAM: Optimizing saliency maps for interpretability"
collection: publications
permalink: /publication/xai-opticam
excerpt: 'This paper is about how to optimize saliency maps for interpretability.'
date: 2024-11-01
venue: 'Computer Vision and Image Understanding'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S1077314224001826'
citation: 'Zhang, H., Torres, F., Sicre, R., Avrithis, Y., & Ayache, S. (2024). Opti-CAM: Optimizing saliency maps for interpretability. Computer Vision and Image Understanding, 248, 104101.'
---

Methods based on class activation maps (CAM) provide a simple mechanism to interpret predictions of convolutional neural networks by using linear combinations of feature maps as saliency maps. By contrast, masking-based methods optimize a saliency map directly in the image space or learn it by training another network on additional data. In this work we introduce Opti-CAM, combining ideas from CAM-based and masking-based approaches. Our saliency map is a linear combination of feature maps, where weights are optimized per image such that the logit of the masked image for a given class is maximized. We also fix a fundamental flaw in two of the most common evaluation metrics of attribution methods. On several datasets, Opti-CAM largely outperforms other CAM-based approaches according to the most relevant classification metrics. We provide empirical evidence supporting that localization and classifier interpretability are not necessarily aligned.

[paper](https://www.sciencedirect.com/science/article/pii/S1077314224001826)
[code](https://github.com/hanwei0912/OptiCAM)

