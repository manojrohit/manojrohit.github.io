---
title: "Pruning CNNs  for  LiDAR-based  Perception  in  Resource  Constrained Environments"
collection: publications
permalink: /publications/breaking-bed
venue: "IntelliSys 2021"
date: 2021-11-07
[[Arxiv]](https://arxiv.org/pdf/2103.08031.pdf)
---

## Abstract
Deploying convolutional neural networks (CNNs) for embedded applications presents many challenges in balancing resource-efficiency and task-related accuracy. These two aspects have been well-researched in the field of CNN compression. In real-world applications, a third important aspect comes into play, namely the robustness of the CNN. In this paper, we thoroughly study the robustness of uncompressed, distilled, pruned and binarized neural networks against white-box and black-box adversarial attacks (FGSM, PGD, C&W, DeepFool, LocalSearch and GenAttack). These new insights facilitate defensive training schemes or reactive filtering methods, where the attack is detected and the input is discarded and/or cleaned. Experimental results are shown for distilled CNNs, agent-based state-of-the-art pruned models, and binarized neural networks (BNNs) such as XNOR-Net and ABC-Net, trained on CIFAR-10 and ImageNet datasets. We present evaluation methods to simplify the comparison between CNNs under different attack schemes using loss/accuracy levels, stress-strain graphs, box-plots and class activation mapping (CAM). Our analysis reveals susceptible behavior of
uncompressed and pruned CNNs against all kinds of attacks. The distilled models exhibit their strength against all white box attacks with an
exception of C&W. Furthermore, binary neural networks exhibit resilient
behavior compared to their baselines and other compressed variants.

[[Arxiv]](https://arxiv.org/pdf/2103.08031.pdf)

Citation:
    
    @InProceedings{Vemparala_2021_IV,
        author    = {Manoj Rohit Vemparala and Alexander Frickenstein and Nael Fasfous and Lukas Frickenstein and Qi Zhao and Sabine Kuhn and Daniel Ehrhardt and Yuankai Wu and Christian Unger and Naveen Shankar Nagaraja and Walter Stechele},
        title     = {BreakingBED - Breaking Binary and Efficient Deep Neural Networks by Adversarial Attacks},
        booktitle = {IntelliSys conference 2021 },
        month     = {September},
        year      = {2021}
    }