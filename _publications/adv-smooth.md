---
title: "Smooth adversarial examples"
collection: publications
permalink: /publication/adv-smooth
excerpt: 'This paper is about how to generate smooth adversarial perturbations.'
date: 2020-12-01
venue: 'EURASIP Journal on Information Security'
paperurl: 'https://link.springer.com/article/10.1186/s13635-020-00112-z'
citation: 'Zhang, H., Avrithis, Y., Furon, T., & Amsaleg, L. (2020). Smooth adversarial examples. EURASIP Journal on Information Security, 2020, 1-12.'
---

This paper investigates the visual quality of the adversarial examples. Recent papers propose to smooth the perturbations to get rid of high frequency artifacts. In this work, smoothing has a different meaning as it perceptually shapes the perturbation according to the visual content of the image to be attacked. The perturbation becomes locally smooth on the flat areas of the input image, but it may be noisy on its textured areas and sharp across its edges.This operation relies on Laplacian smoothing, well-known in graph signal processing, which we integrate in the attack pipeline. We benchmark several attacks with and without smoothing under a white box scenario and evaluate their transferability. Despite the additional constraint of smoothness, our attack has the same probability of success at lower distortion.

[Paper](https://link.springer.com/article/10.1186/s13635-020-00112-z)
[Code](https://github.com/hanwei0912/SmoothAdversarialExamples)
