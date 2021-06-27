---
title: "Investigating Binary Neural Networks for Traffic Sign Detection and Recognition"
collection: publications
permalink: /publications/binary-traffic-sign-detector
venue: "IV 2021"
date: 2021-11-07
[[Arxiv Version Soon]](https://arxiv.org/)
---

## Abstract
 Traffic sign detection is crucial for enabling autonomous vehicles to navigate in real-world streets, which must be  carried  out  with  high  accuracy  and  in  real-time.  CNNs have  become  one  of  the  standard  approaches  for  traffic  sign detection research in recent years. The use of CNNs has allowed the   development   of   traffic   sign   detectors   that   are   capable of  achieving  prediction  accuracies  similar  to  those  of  human drivers.  However,  most  CNNs  do  not  run  in  real-time  due  to the  high  number  of  computational  operations  involved  duringthe  inference  phase.  This  hinders  the  deployment  of  CNNs  in autonomous vehicles despite their high prediction accuracy. In this  paper,  we  explore  BNNs  to  tackle  this  problem.  BNNs binarize  the  full-precision  weights  and  activations  of  a  CNN, drastically reducing the complexity of the computational operations required for inference, while at the same time maintaining the  architectural  parameters,  as  well  as  spatial  dimensions  of the  input  image.  This  reduces  the  memory  required  to  run the  model  and  enables  faster  inference  time.  We  carry  out  in-depth studies on applying BNNs for traffic sign detection using real-world datasets. We observe an improvement of 11.63× for normalized  compute  complexity,  while  suffering  only  3.93  pp in  detection  accuracy  on  GTSDB  dataset.

[[Arxiv Version Soon]](https://arxiv.org/)

Citation:
    
    @InProceedings{Chen_2021_IV,
        author    = {Chen, Ee Heng and Vemparala, Manoj Rohit and Fasfous, Nael and Frickenstein, Alexander and Mzid, Ahmed and Nagaraja, Naveen Shankar and  Zeisler, Joran and Stechele, Walter},
        title     = {Investigating Binary Neural Networks for Traffic Sign Detection and Recognition},
        booktitle = {Intelligent Vehicles Symposium},
        month     = {July},
        year      = {2021}
    }