---
title: "Rain Streaks Removal for Single Image via Kernel-Guided Convolutional Neural Network"
collection: publications
permalink: /publications/KGCNN
---
[[PDF]](http://owuchangyuo.github.io/files/KGCNN.pdf)

## Abstract
Recently emerged deep learning methods have achieved great success in single image rain streaks removal. However, existing methods ignore an essential factor in the rain streaks generation mechanism, i.e., the motion blur leading to the line pattern appearances. Thus, they generally produce overderaining or underderaining results. In this article, inspired by the generation mechanism, we propose a novel rain streaks removal framework using a kernel-guided convolutional neural network (KGCNN), achieving state-of-the-art performance with a simple network architecture. More precisely, our framework consists of three steps. First, we learn the motion blur kernel by a plain neural network, termed parameter network, from the detail layer of a rainy patch. Then, we stretch the learned motion blur kernel into a degradation map with the same spatial size as the rainy patch. Finally, we use the stretched degradation map together with the detail patches to train a deraining network with a typical ResNet architecture, which produces the rain streaks with the guidance of the learned motion blur kernel. Experiments conducted on extensive synthetic and real data demonstrate the effectiveness of the proposed KGCNN, in terms of rain streaks removal and image detail preservation.
