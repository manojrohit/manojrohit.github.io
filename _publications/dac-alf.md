---
title: "ALF: Autoencoder-based Low-rank Filter-sharing for Efficient Convolutional Neural Networks"
collection: publications
permalink: /publications/dac-alf
venue: "DAC 2020"
date: 2020-19-07
[[Arxiv]](https://arxiv.org/pdf/2007.13384.pdf)
---

## Abstract
Closing the gap between the hardware requirements of state-of-the-art convolutional neural networks and the limited resources constraining embedded applications is the next big challenge in deep learning research. The computational complexity and memory footprint of such neural networks are typically daunting for deployment in resource constrained environments. Model compression techniques, such as pruning, are emphasized among other optimization methods for solving this problem. Most existing techniques require domain expertise or result in irregular sparse representations, which increase the burden of deploying deep learning applications on embedded hardware accelerators. In this paper, we propose the autoencoder-based low-rank filter-sharing technique technique (ALF). When applied to various networks, ALF is compared to state-of-the-art pruning methods, demonstrating its efficient compression capabilities on theoretical metrics as well as on an accurate, deterministic hardware-model. In our experiments, ALF showed a reduction of 70\% in network parameters, 61\% in operations and 41\% in execution time, with minimal loss in accuracy.

[[Arxiv]](https://arxiv.org/pdf/2007.13384.pdf)

Citation:
    
    @article{Frickenstein2020ALFAL,
      title={ALF: Autoencoder-based Low-rank Filter-sharing for Efficient Convolutional Neural Networks},
      author={Alexander Frickenstein and M. Vemparala and N. Fasfous and Laura Hauenschild and N. Nagaraja and C. Unger and W. Stechele},
      journal={2020 57th ACM/IEEE Design Automation Conference (DAC)},
      year={2020},
      pages={1-6}
    }