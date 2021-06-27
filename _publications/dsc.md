---
title: "DSC: Dense-Sparse Convolution for Vectorized Inference of Convolutional Neural Networks"
collection: publications
permalink: /publications/dsc
venue: "CVPR-W 2019"
date: 2019-16-06
[[Arxiv]](https://openaccess.thecvf.com/content_CVPRW_2019/papers/SAIAD/Frickenstein_DSC_Dense-Sparse_Convolution_for_Vectorized_Inference_of_Convolutional_Neural_Networks_CVPRW_2019_paper.pdf)
---

## Abstract
The efficient applications of Convolutional Neural Networks (CNNs) in automotive-rated and safety critical hardware-accelerators require an interplay of DNN design optimization, programming techniques and hardware resources. Ad-hoc pruning would result in irregular sparsity and compression leading in very inefficient real world applications. Therefore, the proposed methodology, called Dense-Sparse Convolution, makes use of the right balance between pruning regularity, quantization and the underlying vectorized hardware. Different word length compute units, e.g. CPU, are used for low latency inference of the spares CNNs. The proposed open source CPU-kernel scales along with the vector word length and the number of cores.

[[CVPR Version]](https://openaccess.thecvf.com/content_CVPRW_2019/papers/SAIAD/Frickenstein_DSC_Dense-Sparse_Convolution_for_Vectorized_Inference_of_Convolutional_Neural_Networks_CVPRW_2019_paper.pdf)

Citation:
    
    @INPROCEEDINGS{Frickenstein_2019_DSC,
      author={Frickenstein, Alexander and Vemparala, Manoj Rohit and Unger, Christian and Ayar, Fatih and Stechele, Walter},
      booktitle={2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW)}, 
      title={DSC: Dense-Sparse Convolution for Vectorized Inference of Convolutional Neural Networks}, 
      year={2019},
      volume={},
      number={},
      pages={1353-1360},
      doi={10.1109/CVPRW.2019.00175}}