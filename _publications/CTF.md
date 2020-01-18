---
title: "A Coarse-to-Fine Method for Infrared Small Target Detection"
collection: publications
permalink: /publications/CTF
---  
[[PDF]](https://owuchangyuo.github.io/files/CTF.pdf) 

## Abstract
Infrared small target detection in a complex background is a challenging problem. A complex background generally contains structured edges, unstructured clutter, and noise, which completely have different properties. It is very difficult to separate small target from these interferences by exploiting one property. To solve this problem, we propose a coarse-to fine method to gradually detect small target. In the coarse phase, nonlocal self-similarity property of the structured edges is exploited so as to separate the structured edges from the other components, such as the random noise, the unstructured clutter, and also the small target. In the fine phase, we utilize the local contrast prior of the small target in a local region so as to distinguish the small target from the unstructured clutter and noise. Multiscale information is further introduced to accommodate the changing size of the small target. This progressive detection pipeline utilizes the nonlocal, local, and multiscale information in a single image, which facilitates gradually differentiating the
small target from the structured edges, unstructured clutter, and noise. Extensive experimental results demonstrate that the proposed method outperforms the state-of-the-art methods.
