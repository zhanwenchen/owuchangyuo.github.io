---
title: "Learning Blind Denoising Network for Noisy Image Deblurring"
collection: publications
permalink: /publications/BDN
---  
[[PDF]](https://owuchangyuo.github.io/files/BDN.pdf) 

## Abstract
Noisy image deblurring is to recover the blurry image in the presence of the random noise. The key to this problem is to know the noise level in each iteration. The existing methods manually adjust the regularization parameter for varying noise levels, which are quite inaccuracy and tedious for practical application. In this work, we discover that the noise level and the denoiser are tightly coupled. Consequently, we propose a blind denoising convolutional neural network (BDCNN)
consisting of two stages: a down-sampling regression network for estimating noise level and a fully convolutional network for denoising, such that our model could adaptively handle the unknown noise level during iterations. Further, the BDCNN functions as a discriminative prior and is plugged into the iterative deblurring framework for noisy image deblurring. Experimental results demonstrate that the proposed method outperforms state-of-the-art methods in terms of practicability
and performance.
