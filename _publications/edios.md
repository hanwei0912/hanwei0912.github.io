---
title: "Eidos: Efficient, Imperceptible Adversarial 3D Point Clouds"
collection: publications
permalink: /publication/adv-nerfail
excerpt: 'This paper is about adversarial robustness on 3D point clouds.'
date: 2024-11-25
venue: 'International Symposium on Dependable Software Engineering: Theories, Tools, and Applications (SETTA 2024)'
paperurl: 'https://link.springer.com/chapter/10.1007/978-981-96-0602-3_17'
citation: 'Zhang, H., Cheng, L., He, Q., Huang, W., Li, R., Sicre, R., ... & Zhang, L. (2024, November). Eidos: Efficient, imperceptible adversarial 3d point clouds. In International Symposium on Dependable Software Engineering: Theories, Tools, and Applications (pp. 310-326). Singapore: Springer Nature Singapore.'
---

Classification of 3D point clouds is a challenging machine learning (ML) task with important real-world applications in a spectrum from autonomous driving and robot-assisted surgery to earth observation from low orbit. As with other ML tasks, classification models are notoriously brittle in the presence of adversarial attacks. These are rooted in imperceptible changes to inputs with the effect that a seemingly well-trained model ends up misclassifying the input. This paper adds to the understanding of adversarial attacks by presenting Eidos, a framework providing Efficient Imperceptible aDversarial attacks on 3D pOint cloudS. Eidos supports a diverse set of imperceptibility metrics. It employs an iterative, two-step procedure to identify optimal adversarial examples, thereby enabling a runtime-imperceptibility trade-off. We provide empirical evidence relative to several popular 3D point cloud classification models and several established 3D attack methods, showing Eidos ’ superiority with respect to efficiency as well as imperceptibility.

[paper](https://link.springer.com/chapter/10.1007/978-981-96-0602-3_17)
[code](https://github.com/Uzukidd/eidos)
