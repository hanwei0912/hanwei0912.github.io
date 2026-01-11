---
title: "IPA-NeRF: Illusory Poisoning Attack Against Neural Radiance Fields"
collection: publications
permalink: /publication/IPA
excerpt: 'This paper is about adversarial poisoning attack on NeRF.'
date: 2024-07-16
venue: 'Proceedings of ECAI 2024'
paperurl: 'https://arxiv.org/pdf/2407.11921'
citation: 'Jiang, W., Zhang, H., Zhao, S., Guo, Z., & Wang, H. (2024). Ipa-nerf: Illusory poisoning attack against neural radiance fields. arXiv preprint arXiv:2407.11921.'
---

Neural Radiance Field (NeRF) represents a significant advancement in computer vision, offering implicit neural network-based scene representation and novel view synthesis capabilities. Its applications span diverse fields including robotics, urban mapping, autonomous navigation, virtual reality/augmented reality, etc., some of which are considered high-risk AI applications. However, despite its widespread adoption, the robustness and security of NeRF remain largely unexplored. In this study, we contribute to this area by introducing the Illusory Poisoning Attack against Neural Radiance Fields (IPA-NeRF). This attack involves embedding a hidden backdoor view into NeRF, allowing it to produce predetermined outputs, i.e. illusory, when presented with the specified backdoor view while maintaining normal performance with standard inputs. Our attack is specifically designed to deceive users or downstream models at a particular position while ensuring that any abnormalities in NeRF remain undetectable from other viewpoints. Experimental results demonstrate the effectiveness of our Illusory Poisoning Attack, successfully presenting the desired illusory on the specified viewpoint without impacting other views. Notably, we achieve this attack by introducing small perturbations solely to the training set. 

[paper](https://arxiv.org/pdf/2407.11921)
[code](https://github.com/jiang-wenxiang/IPA-NeRF)
