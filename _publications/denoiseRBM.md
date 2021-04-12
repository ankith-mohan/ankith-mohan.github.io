---
title: "Graph Signal Recovery using Restricted Boltzmann Machines"
collection: publications
permalink: /publications/denoiseRBM
venue: "ArXiv 2020"
date: 2020-11-20
citation: '<b>Ankith Mohan</b>, Aiichiro Nakano, Emilio Ferrara. <i>Preprint. arXiv:2011.10549</i>'
---

[[ArXiv]](https://arxiv.org/pdf/2011.10549.pdf)[[Code]](https://github.com/ankithmo/denoiseRBM)

## Abstract
Given: (a) clean training dataset, (b) trained graph machine learning pipeline, and (c) noisy test dataset; how do we make the pipeline robust to such noise? In an attempt to answer this question, we propose a modification to the pipeline that exploits both the content addressability of a restricted Boltzmann machine and the message passing capabilities of a graph neural network. We investigate which of the hidden layers of the pipeline is best suited for our proposed modification. By establishing that a decrease in mutual information indicates an increase in prediction accuracy which is in turn driven by progressive geometric clustering of the samples belonging to the same class, we attempt to explain the behavior exhibited by the modified pipeline. Empirical results demonstrate that our approach makes the pipeline robust to some real-world noisy scenarios in citation datasets.
