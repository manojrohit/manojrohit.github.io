---
title: "An Efficient FPGA Accelerator Design for Optimized CNNs Using OpenCL"
collection: publications
permalink: /publications/winocnn
venue: "ARCS 2019"
date: 2019-20-05
[[Springer link]](https://www.springerprofessional.de/en/an-efficient-fpga-accelerator-design-for-optimized-cnns-using-op/16718546)
---

## Abstract
Convolutional Neural Networks (CNNs) require highly parallel Hardware (HW) accelerators in the form of Graphical Processing Units (GPUs), Application Specific Integrated Circuits (ASICs) or Field Programmable Gate Arrays (FPGAs) to build low latency solutions necessary for implementing image processing applications. FPGAs have the ability to provide a right balance between flexibility, performance and energy efficiency. The design of FPGA based accelerator design traditionally required a tedious Register Transfer Level (RTL) design flow process. To improve design productivity, the proposed work uses High-Level Synthesis (HLS), described in OpenCL, to generate the FPGA bitstream for the CNN model. The 2D Winograd transformation is integrated in the pipeline to reduce the overall number of Multiply and Accumulate (MAC) operations in the CNN. Instead of increasing the batch size to improve the throughput, this work discusses a mixed precision approach which can counter the limited memory bandwidth issue within the CNN. The obtained results are competitive against other FPGA based implementations proposed in literature. The proposed accelerator can achieve more than  1.9x higher energy efficiency compared to an embedded Nvidia Jetson TX1 implementation of VGG-16.

[[Springer link]](https://www.springerprofessional.de/en/an-efficient-fpga-accelerator-design-for-optimized-cnns-using-op/16718546)

Citation:
    
    @InProceedings{Vemparala_2019_WinoCNN,
    author="Vemparala, Manoj Rohit
    and Frickenstein, Alexander
    and Stechele, Walter",
    title="An Efficient FPGA Accelerator Design for Optimized CNNs Using OpenCL",
    booktitle="Architecture of Computing Systems -- ARCS 2019",
    year="2019",
    publisher="Springer International Publishing",
    address="Cham",
    pages="236--249",
    }