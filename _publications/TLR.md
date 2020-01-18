---
title: "Transformed Low-rank Model for Line Pattern Noise Removal"
collection: publications
permalink: /publications/TLR
---
[[PDF]](https://owuchangyuo.github.io/files/TLR.pdf) 


## Abstract
This paper addresses the problem of line pattern noise removal from a single image, such as rain streak, hyperspectral stripe and so on. Most of the previous methods model the line pattern noise in original image domain, which fail to explicitly exploit the directional characteristic, thus resulting in a redundant subspace with poor representation ability for those line pattern noise. To achieve a compact
subspace for the line pattern structure, in this work, we incorporate a transformation into the image decomposition model so that maps the input image to a domain where the line pattern appearance has an extremely distinct low-rank structure, which naturally allows us to enforce a low-rank prior to extract the line pattern streak/stripe from the noisy image. Moreover, the random noise is usually mixed up with the line pattern noise, which makes the challenging problem much more difficult. While previous methods resort to the spectral or temporal correlation of the multi-images, we give a detailed analysis between the noisy and clean image in both local gradient and nonlocal domain, and propose a compositional directional total variational and low-rank prior for the image layer, thus to simultaneously accommodate both types of noise. The proposed method has been evaluated on two different tasks, including remote sensing image mixed random-stripe noise removal and rain streak removal, all of which obtain very impressive performances.