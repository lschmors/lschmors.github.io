---
title: "TRACE: Time-series Representation through Averaging and Contrastive Embeddings"
collection: publications
category: conferences
permalink: /publication/2025-neurips-trace
excerpt: 'A novel framework for visualizing neural time-series data using contrastive learning'
date: 2025-12-06
venue: 'The Thirty-ninth Annual Conference on Neural Information Processing Systems (NeurIPS)'
paperurl: 'https://arxiv.org/abs/2506.04906'
citation: 'Schmors, L., et al. (2025). "TRACE: Time-series Representation through Averaging and Contrastive Embeddings." <i>NeurIPS 2025</i>.'
---

## Abstract
Modern neural recording techniques such as two-photon imaging or Neuropixel probes allow to acquire vast time-series datasets with responses of hundreds or thousands of neurons. Contrastive learning is a powerful self-supervised framework for learning representations of complex datasets. Existing applications for neural time series rely on generic data augmentations and do not exploit the multi-trial data structure inherent in many neural datasets. Here we present TRACE, a new contrastive learning framework that averages across different subsets of trials to generate positive pairs. TRACE allows to directly learn a two-dimensional embedding, combining ideas from contrastive learning and neighbor embeddings. We show that TRACE outperforms other methods, resolving fine response differences in simulated data. Further, using in vivo recordings, we show that the representations learned by TRACE capture both biologically relevant continuous variation, cell-type-related cluster structure, and can assist data quality control.

## Download
[Download paper here](https://openreview.net/pdf/4676a4db97cecf0a8637df37ac0d9da81195e796.pdf)
