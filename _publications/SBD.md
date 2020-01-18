---
title: "A MAP-based Algorithm for Spectroscopic Semi-blind Deconvolution"
collection: publications
permalink: /publications/SBD
---  
[[PDF]](https://owuchangyuo.github.io/files/SBD.pdf) 

## Abstract
Spectroscopic data often suffer from common problems of bands overlapping and random noise. In this paper, we show that the issue of overlapping peaks can be considered as a maximum a posterior (MAP) problem and be solved by minimizing an object functional that includes a likelihood term and two prior terms. In the MAP framework, the likelihood probability density function (PDF) is constructed based on a spectral observation model, a robust Huber–Markov model is used as spectra prior PDF, and the kernel prior is described based on a parametric Gaussian function. Moreover, we describe an efficient optimization scheme that alternates between latent spectrum recovery and blur kernel estimation until convergence. The major novelty of the proposed algorithm is that it can estimate
the kernel slit width and latent spectrum simultaneously. Comparative results with other deconvolution methods suggest that the proposed method can recover spectral structural details as well as suppress noise effectively.
