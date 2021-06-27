---
title: "L2PF -- Learning to Prune Faster"
collection: publications
permalink: /publications/l2pf
venue: "CVIP 2020"
date: 2020-02-12
[[Paper]](https://arxiv.org/pdf/2101.02663.pdf)
---

## Abstract
Various applications in the field of autonomous driving are based on convolutional neural networks (CNNs), especially for processing camera data. The optimization of such CNNs is a major challenge in continuous development. Newly learned features must be brought into vehicles as quickly as possible, and as such, it is not feasible to spend redundant GPU hours during compression. In this context, we present Learning to Prune Faster which details a multi-task, try-and-learn method, discretely learning redundant filters of the CNN and a continuous action of how long the layers have to be fine-tuned. This allows us to significantly speed up the convergence process of learning how to find an embedded-friendly filter-wise pruned CNN. For ResNet20, we have achieved a compression ratio of 3.84 x with minimal accuracy degradation. Compared to the state-of-the-art pruning method, we reduced the GPU hours by 1.71 x.

[[Arxiv]](https://arxiv.org/pdf/2101.02663.pdf)

Citation:
    
    @inproceedings{Vemparala2020L2PFL,
      title={L2PF - Learning to Prune Faster},
      author={M. Vemparala and N. Fasfous and Alexander Frickenstein and Mhd Ali Moraly and Aquib Jamal and Lukas Frickenstein and C. Unger and N. Nagaraja and W. Stechele},
      booktitle={CVIP},
      year={2020}
    }