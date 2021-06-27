---
title: "Binary DAD-Net: Binarized Driveable Area Detection Network for Autonomous Driving"
collection: publications
permalink: /publications/bin-dad
venue: "ICRA 2020"
date: 2020-31-05
[[Arxiv]](https://arxiv.org/pdf/2006.08178.pdf)
---

## Abstract
Driveable area detection is a key component for various applications in the field of autonomous driving (AD), such as ground-plane detection, obstacle detection and maneuver planning. Additionally, bulky and over-parameterized networks can be easily forgone and replaced with smaller networks for faster inference on embedded systems. The driveable area detection, posed as a two class segmentation task, can be efficiently modeled with slim binary networks. This paper proposes a novel binarized driveable area detection network (binary DAD-Net), which uses only binary weights and activations in the encoder, the bottleneck, and the decoder part. The latent space of the bottleneck is efficiently increased (x32 -> x16 downsampling) through binary dilated convolutions, learning more complex features. Along with automatically generated training data, the binary DAD-Net outperforms state-of-the-art semantic segmentation networks on public datasets. In comparison to a full-precision model, our approach has a x14.3 reduced compute complexity on an FPGA and it requires only 0.9MB memory resources. Therefore, commodity SIMD-based AD-hardware is capable of accelerating the binary DAD-Net.

[[Arxiv]](https://arxiv.org/pdf/2006.08178.pdf)

Citation:
    
    @article{Frickenstein2020BinaryDB,
      title={Binary DAD-Net: Binarized Driveable Area Detection Network for Autonomous Driving},
      author={Alexander Frickenstein and M. Vemparala and J. Mayr and N. Nagaraja and C. Unger and Federico Tombari and W. Stechele},
      journal={2020 IEEE International Conference on Robotics and Automation (ICRA)},
      year={2020},
      pages={2295-2301}
    }