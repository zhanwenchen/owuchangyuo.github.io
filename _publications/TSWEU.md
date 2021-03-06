---
title: "Toward Universal Stripe Removal Via Wavelet-based Deep Convolutional Neural Network"
collection: publications
permalink: /publications/TSWEU
---
[[PDF]](http://owuchangyuo.github.io/files/TSWEU.pdf)

## Abstract
Stripe noise from different remote-sensing imaging systems varies considerably in terms of the response, length, angle, and periodicity. Due to the complex distributions of different stripes, the destriping results of previous methods may be over-smoothed or contain residual stripe. To overcome this key problem, we provide a comprehensive analysis of existing destriping methods and propose a deep convolutional neural network (CNN) for handling various kinds of stripe. Moreover, previous methods individually model the stripe or the image priors, which may lose the relationship between them. In this work, a two-stream CNN is designed to simultaneously model the stripe and image, which better facilitates distinguishing them from each other. Moreover, we incorporate the wavelet into our CNN model for better directional feature representation. Therefore, the CNN learns the discriminative representation from the external dataset, while the wavelet models the internal directionality of the stripe, in which both the internal and external priors are beneficial to the destriping task. In addition, the wavelet extracts the multiscale information with a larger receptive field for global contextual information modeling; thus, we can better distinguish the stripe from the similar image line pattern structures. The proposed method has been extensively evaluated on a number of datasets and outperforms the stateof-the-art methods by a substantially large margin in terms of quantitative and qualitative assessments, speed, and robustness.
