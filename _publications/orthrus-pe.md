---
title: "OrthrusPE: runtime reconfigurable processing elements for binary neural networks"
collection: publications
permalink: /publications/orthrus-pe
venue: "DATE 2020"
date: 2020-21-04
[[ACM]](https://dl.acm.org/doi/abs/10.5555/3408352.3408731)
---

## Abstract
Recent advancements in Binary Neural Networks (BNNs) have yielded promising results, bringing them a step closer to their full-precision counterparts in terms of prediction accuracy. These advancements were brought about by additional arithmetic and binary operations, in the form of scale and shift operations (fixed-point) and convolutions with multiple weight and activation bases (binary). In this paper, we propose OrthrusPE, a runtime reconfigurable processing element (PE) which is capable of executing all the operations required by modern BNNs while improving resource utilization and power efficiency. More precisely, we exploit DSP48 blocks on off-the-shelf FPGAs to compute binary Hadamard products (for binary convolutions) and fixed-point arithmetic (for scaling, shifting, batch norm, and non-binary layers), thereby utilizing the same hardware resource for two distinct, critical modes of operation. Our experiments show that common PE implementations increase dynamic power consumption by 67%, while requiring 39% more lookup tables, when compared to an OrthrusPE implementation.
[[ACM]](https://dl.acm.org/doi/abs/10.5555/3408352.3408731)

Citation:
    
    @inproceedings{2020_Fasfous_OrthrusPE,
    author = {Fasfous, Nael and Vemparala, Manoj Rohit and Frickenstein, Alexander and Stechele, Walter},
    title = {OrthrusPE: Runtime Reconfigurable Processing Elements for Binary Neural Networks},
    year = {2020},
    booktitle = {Proceedings of the 23rd Conference on Design, Automation and Test in Europe},
    series = {DATE '20}
    }