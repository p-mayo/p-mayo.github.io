---
title: "Representation learning via cauchy convolutional sparse coding"
collection: publications
permalink: /publication/2021-07-12_representation_learning_cauchy_convolutional_sparse_coding
excerpt: 'A further step in the exploration of the Cauchy distribution in the field of representation learning.'
date: 2021-07-12
venue: 'IEEE Access'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9481269/'
citation: '<b>Perla Mayo</b>, Oktay Karakus, Robin Holmes, and Alin Achim, (2021). &quot;Representation learning via cauchy convolutional sparse coding.&quot; <i>IEEE Access</i>.'
---

## Abstract
In representation learning, Convolutional Sparse Coding (CSC) enables unsupervised learning of 
features by jointly optimising both an ℓ2 -norm fidelity term and a sparsity enforcing penalty. 
This work investigates using a regularisation term derived from an assumed Cauchy prior for the 
coefficients of the feature maps of a CSC generative model. The sparsity penalty term resulting 
from this prior is solved via its proximal operator, which is then applied iteratively, element-wise, 
on the coefficients of the feature maps to optimise the CSC cost function. The performance of 
the proposed Iterative Cauchy Thresholding (ICT) algorithm in reconstructing natural images is 
compared against algorithms based on minimising standard penalty functions via soft and hard 
thresholding as well as against the Iterative Log-Thresholding (ILT) method. ICT outperforms 
the Iterative Hard Thresholding (IHT), Iterative Soft Thresholding (IST), and ILT algorithms 
in most of our reconstruction experiments across various datasets, with an average Peak Signal 
to Noise Ratio (PSNR) of up to 11.30 dB, 7.04 dB, and 7.74 dB over IST, IHT, and ILT respectively. 
The source code for the implementation of the proposed approach is publicly available at 
https://github.com/p-mayo/cauchycsc

[Download paper here](https://ieeexplore.ieee.org/abstract/document/9481269/)
[Code available here](https://github.com/p-mayo/cauchycsc)

Recommended citation: P. Mayo, O. Karakuş, R. Holmes and A. Achim, 
"Representation Learning via Cauchy Convolutional Sparse Coding," 
in <i>IEEE Access</i>, vol. 9, pp. 100447-100459, 2021, doi: 10.1109/ACCESS.2021.3096643.