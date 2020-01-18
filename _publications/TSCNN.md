---
title: "Two-Stage Convolutional Neural Network for Medical Noise Removal via Image Decomposition"
collection: publications
permalink: /publications/TSCNN
---

[[PDF]](https://owuchangyuo.github.io/files/TSCNN.pdf)

## Abstract
Most of existing medical image denoising methods focus on estimating either the image or the residual noise. Moreover, they are usually designed for one specific noise with a strong assumption of the noise distribution. However, not only the random independent Gaussian or speckle noise but also the structurally correlated ring or stripe noise, are ubiquitous in various medical imaging instruments. Explicitly modeling the distributions of these complex noises in the medical image is extremely hard. They cannot be accurately held by the Gaussian
or mixture of Gaussian model. To overcome the two drawbacks, in this work, we propose to treat the image and noise components equally and convert the image denoising task into an image decomposition problem naturally. More precisely, we present a two-stage deep convolutional neural network (CNN) to model both the noise and the medical image simultaneously. On the one hand, we utilize both the image and noise to separate them better. On the other hand, the noise sub-network serves as a noise estimator which guides the image sub-network with sufficient information about the noise, thus we could easily handle different noise distributions and noise levels. To better cope with the gradient vanishing problem in this very deep network, we introduce both the short-term and long-term connections in the network which could promote the information propagation between different layers efficiently. Extensive experiments have been performed on several kinds of medical noise images, such as the computed tomography and ultrasound images, and the proposed method has consistently outperformed state-of-the-art denoising methods.
