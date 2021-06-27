---
title: "Adversarial Robust Model Compression using In-Train Pruning"
collection: publications
permalink: /publications/robust-pruning
venue: "CVPR-W 2021"
date: 2021-20-06
---

## Abstract
Efficiently deploying learning-based systems on embedded hardware is challenging for various reasons, two of which are considered in this paper: The model’s size and its robustness against attacks. Both need to be addressed even-handedly. We combine adversarial training and model pruning in a joint formulation of the fundamental learning objective during training. Unlike existing post-train pruning approaches, our method does not use heuristics and eliminates the need for a pre-trained model. This allows for a classifier which is robust against attacks and enables better compression of the model, reducing its computational effort. In comparison to prior work, our approach yields 6.21 pp higher accuracy for an 85 % reduction in parameters for ResNet20 on the CIFAR-10 dataset.

[[CVPR Version]](https://openaccess.thecvf.com/content/CVPR2021W/SAIAD/papers/Vemparala_Adversarial_Robust_Model_Compression_Using_In-Train_Pruning_CVPRW_2021_paper.pdf) [[Slide]](http://manojrohit.github.io/files/final_presentation_saiad_github.pdf)

Citation:
   
    @InProceedings{Vemparala_2021_CVPR,
        author    = {Vemparala, Manoj-Rohit and Fasfous, Nael and Frickenstein, Alexander and Sarkar, Sreetama and Zhao, Qi and Kuhn, Sabine and Frickenstein, Lukas and Singh, Anmol and Unger, Christian and Nagaraja, Naveen-Shankar and Wressnegger, Christian and Stechele, Walter},
        title     = {Adversarial Robust Model Compression Using In-Train Pruning},
        booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
        month     = {June},
        year      = {2021},
        pages     = {66-75}
    }