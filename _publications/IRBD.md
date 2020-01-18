---
title: "Iteratively Reweighted Blind Deconvolution With Adaptive Regularization Parameter Estimation"
collection: publications
permalink: /publications/IRBD
---  
[[PDF]](https://owuchangyuo.github.io/files/IRBD.pdf)
## Abstract
In many realistic image processing applications, the acquired images often suffer from mixed noises and blurring, which greatly degrade the image quality. In this paper, we propose an iteratively reweighted blind deconvolution method with robust regression for obtaining high quality images with mixed noises present. First, we construct a variational regularization model, including a robust regression data term with an adaptive reweighted least square criterion, which is robust to the mixed noises. To preserve the sharp edges and suppress the noise, a total variation-based regularization term for the image is incorporated into the model. Moreover, a Laplacian regularization term is imposed on the point spread function (PSF) for better smoothness. The subsequent optimization problems for the image and the PSF are solved using the limited-memory BFGS-B algorithm suitable for the large-scale problems. In addition, to improve the practicality of the method, a variant of the generalized cross validation method is derived and adopted to automatically estimate the regularization parameters for the image and the PSF. Experiments on simulated and real images demonstrate that the proposed method is superior to the state-of-the-art methods in terms of both subjective measure and visual quality.
