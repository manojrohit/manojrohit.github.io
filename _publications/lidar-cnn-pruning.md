---
title: "Pruning CNNs  for  LiDAR-based  Perception  in  Resource  Constrained Environments"
collection: publications
permalink: /publications/lidar-cnn-pruning
venue: "3D-DLAD 2021"
date: 2021-11-07
[[Arxiv Version Soon]](https://arxiv.org/)
---

## Abstract
Deep  neural  networks  provide  high  accuracy  for perception.  However  they  require  high  computational  power. In particular, LiDAR-based object detection delivers good accuracy and real-time performance, but demands high computation due   to   expensive   feature-extraction   from   point   cloud   data in  the  encoder  and  backbone  networks.  We  investigate  the model complexity versus accuracy trade-off using reinforcement learning based pruning for PointPillars, a recent LiDAR-based 3D  object  detection  network.  We  evaluate  the  model  on  the validation dataset of KITTI (80/20-splits) according to the mean average precision (mAP) for the car class. We prune the original PointPillars model (mAP 89.84) and achieve 65.8% reduction in floating point operations (FLOPs) for a marginal accuracy loss. The  compression  corresponds  to  31.7%  reduction  in  inference time  and  35%  reduction  in  GPU  memory  on  GTX  1080  Ti.

[[Arxiv Version Soon]](https://arxiv.org/)

Citation:
    
    @InProceedings{Vemparala_2021_IV,
        author    = {Vemparala, Manoj-Rohit and Singh, Anmol and Mzid, Ahmed and Fasfous, Nael and Frickenstein, Alexander and Mirus, Florain and  Voegel, Hans-Joerg and Nagaraja,Naveen Shankar and Stechele, Walter},
        title     = {Pruning CNNs  for  LiDAR-based  Perception  in  Resource  Constrained Environments},
        booktitle = {3D-DLAD - Intelligent Vehicles Workshop},
        month     = {July},
        year      = {2021}
    }