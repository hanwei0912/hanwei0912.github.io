---
title: "NeRFail: Neural Radiance Fields-Based Multiview Adversarial Attack"
collection: publications
permalink: /publication/adv-nerfail
excerpt: 'This paper is about adversarial robustness on NeRF.'
date: 2024-03-25
venue: 'Proceeding of the 38th AAAI Conference on Artificial Intelligence'
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/view/30113'
citation: 'Jiang, W., Zhang, H., Wang, X., Guo, Z., & Wang, H. (2024, March). Nerfail: Neural radiance fields-based multiview adversarial attack. In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 38, No. 19, pp. 21197-21205).'
---

Adversarial attacks, i.e., generating adversarial perturbations with a small magnitude to deceive deep neural networks, are important for investigating and improving model trustworthiness. Traditionally, the topic was scoped within 2D images without considering 3D multiview information. Benefiting from Neural Radiance Fields (NeRF), one can easily reconstruct a 3D scene with a Multi-Layer Perceptron (MLP) from given 2D views and synthesize photo-realistic renderings of novel vantages. This opens up a door to discussing the possibility of undertaking to attack multiview NeRF network with downstream tasks from different rendering angles, which we denote Neural Radiance Fiels-based multiview adversarial Attack (NeRFail). The goal is, given one scene and a subset of views, to deceive the recognition results of agnostic view angles as well as given views. To do so, we propose a transformation mapping from pixels to 3D points such that our attack generates multiview adversarial perturbations by attacking a subset of images with different views, intending to prevent the downstream classifier from correctly predicting images rendered by NeRF from other views. Experiments show that our multiview adversarial perturbations successfully obfuscate the downstream classifier at both known and unknown views. Notably, when retraining another NeRF on the perturbed training data, we show that the perturbation can be inherited and reproduced. The code can be found at https://github.com/jiang-wenxiang/NeRFail.

[paper](https://ojs.aaai.org/index.php/AAAI/article/view/30113)
[code](https://github.com/jiang-wenxiang/NeRFail)

