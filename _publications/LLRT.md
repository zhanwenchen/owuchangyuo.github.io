---
title: "Hyper-Laplacian Regularized Unidirectional Low-rank Tensor Recovery for Multispectral Image Denoising"
collection: publications
permalink: /publications/LLRT
---  
[[PDF]](https://owuchangyuo.github.io/files/LLRT.pdf)

## Abstract
Recent low-rank based matrix/tensor recovery methods have been widely explored in multispectral images (MSI) denoising. These methods, however, ignore the difference of the intrinsic structure correlation along spatial sparsity, spectral correlation and non-local self-similarity mode. In this paper, we go further by giving a detailed analysis about the rank properties both in matrix and tensor cases, and
figure out the non-local self-similarity is the key ingredient, while the low-rank assumption of others may not hold. This motivates us to design a simple yet effective unidirectional low-rank tensor recovery model that is capable of truthfully capturing the intrinsic structure correlation with reduced computational burden. However, the low-rank models suffer from the ringing artifacts, due to the aggregation of overlapped patches/cubics. While previous methods resort to spatial information, we offer a new perspective by utilizing
the exclusively spectral information in MSIs to address the issue. The analysis-based hyper-Laplacian prior is introduced to model the global spectral structures, so as to indirectly alleviate the ringing artifacts in spatial domain. The advantages of the proposed method over the existing ones are multi-fold: more reasonably structure correlation representability, less processing time, and less artifacts in
the overlapped regions. The proposed method is extensively evaluated on several benchmarks, and significantly outperforms state-of-the-art MSI denoising methods.