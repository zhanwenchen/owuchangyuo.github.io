---
title: "HSI-DeNet: Hyperspectral Image Restoration via Convolutional Neural Network"
collection: publications
permalink: /publications/HSI-DeNet
venue: "IEEE TRANSACTIONS ON GEOSCIENCE AND REMOTE SENSING"
date: 2019-1-21
---
[[PDF]](http://owuchangyuo.github.io/files/HSI-DeNet.pdf)

## Abstract
The spectral and the spatial information in hyperspectral images (HSIs) are the two sides of the same coin. How to jointly model them is the key issue for HSIs’ noise removal, including random noise, structural stripe noise, and dead pixels/lines. In this paper, we introduce the deep convolutional neural network (CNN) to achieve this goal. The learned filters can well extract the spatial information within their local receptive filed. Meanwhile, the spectral correlation can be depicted by the multiple channels of the learned 2-D filters, namely, the number of filters in each layer. The consequent advantages of our CNN-based HSI denoising method (HSI-DeNet) over previous
methods are threefold. First, the proposed HSI-DeNet can be regarded as a tensor-based method by directly learning the filters in each layer without damaging the spectral-spatial structures. Second, the HSI-DeNet can simultaneously accommodate various kinds of noise in HSIs. Moreover, our method is flexible for both single image and multiple images by slightly modifying the channels of the filters in the first and last layers. Last but not least, our method is extremely fast in the testing phase, which makes it more practical for real application. The proposed HSI-DeNet is extensively evaluated on several HSIs, and outperforms the state-of-the-art HSI-DeNets in terms of both speed and performance.
