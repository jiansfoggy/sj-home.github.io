---
title: "XnODR and XnIDR: Two Accurate and Fast Fully Connected Layers for Convolutional Neural Networks"
collection: publications
permalink: /publication/XnODR-XnIDR-paper
excerpt: 'This project proposes a new Fully Connected Layer, XnODR and XnIDR, by fusing CapsFC Layer and Xnorization.'
date: 2023-09-06
venue: ' Journal of Intelligent & Robotic Systems'
slidesurl: 'https://xnodr-xnidr.weebly.com/'
paperurl: 'https://doi.org/10.1007/s10846-023-01952-w'
citation: 'Sun, J., Fard, A.P. & Mahoor, M.H. XnODR and XnIDR: Two Accurate and Fast Fully Connected Layers for Convolutional Neural Networks. <i>J Intell Robot Syst</i> 109, 17 (2023).'
---

**Keywords:** 

CapsNet, XNOR-Net, Dynamic routing, Binarization, Xnorization, Machine learning, Neural network.

**Contributions:**

- We propose a new Fully Connected Layer called XnODR by deploying Xnorization on the CapsFC layer. To be specific, we xnorize the linear projection outside the dynamic routing.
- We propose a new Fully Connected Layer called XnIDR by xnorizing another linear projection inside the dynamic routing.
- XnODR and XnIDR improve the performance (i.e., better accuracy, less FLOPS, and parameters) of both lightweight (MobileNetV2) and heavyweight (ResNet50) models.

**BibTex:**
```markdown
@article{sun2023xnodr,
  title={Xnodr and xnidr: Two accurate and fast fully connected layers for convolutional neural networks},
  author={Sun, Jian and Fard, Ali Pourramezan and Mahoor, Mohammad H},
  journal={Journal of Intelligent \& Robotic Systems},
  volume={109},
  number={1},
  pages={17},
  year={2023},
  publisher={Springer}
}
```