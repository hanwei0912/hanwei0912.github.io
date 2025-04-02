---
title: "Walking on the edge: Fast, low-distortion adversarial examples"
collection: publications
permalink: /publication/adv-bp
excerpt: 'This paper is about how to generate adversarial perturbation efficiently.'
date: 2020-09-04
venue: 'IEEE Transactions on Information Forensics and Security'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9186644'
citation: 'Zhang, H., Avrithis, Y., Furon, T., & Amsaleg, L. (2020). Walking on the edge: Fast, low-distortion adversarial examples. IEEE Transactions on Information Forensics and Security, 16, 701-713.'
---
Adversarial examples of deep neural networks are receiving ever increasing attention because they help in understanding and reducing the sensitivity to their input. This is natural given the increasing applications of deep neural networks in our everyday lives. When white-box attacks are almost always successful, it is typically only the distortion of the perturbations that matters in their evaluation. In this work, we argue that speed is important as well, especially when considering that fast attacks are required by adversarial training. Given more time, iterative methods can always find better solutions. We investigate this speed-distortion trade-off in some depth and introduce a new attack called boundary projection (BP) that improves upon existing methods by a large margin. Our key idea is that the classification boundary is a manifold in the image space: we therefore quickly reach the boundary and then optimize distortion on this manifold.

[Paper]([http://academicpages.github.io/files/paper1.pdf](https://ieeexplore.ieee.org/abstract/document/9186644))
[Code](https://github.com/hanwei0912/walking-on-the-edge-fast-low-distortion-adversarial-examples)
