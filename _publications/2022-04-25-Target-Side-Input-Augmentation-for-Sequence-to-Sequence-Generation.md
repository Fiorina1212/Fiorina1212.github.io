---
title: "Target-Side Input Augmentation for Sequence to Sequence Generation"
collection: publications
permalink: /publication/2022-04-25-Target-Side-Input-Augmentation-for-Sequence-to-Sequence-Generation
date: 2022-04-25
---

[Download paper here](https://openreview.net/forum?id=pz1euXohm4H)

Abstract: Autoregressive sequence generation, a prevalent task in machine learning and natural language processing, generates every target token conditioned on both a source input and previously generated target tokens. Previous data augmentation methods, which have been shown to be effective for the task, mainly enhance source inputs (e.g., injecting noise into the source sequence by random swapping or masking, back translation, etc.) while overlooking the target-side augmentation. In this work, we propose a target-side augmentation method for sequence generation. In training, we use the decoder output probability distributions as soft indicators, which are multiplied with target token embeddings, to build pseudo tokens. These soft pseudo tokens are then used as target tokens to enhance the training. We conduct comprehensive experiments on various sequence generation tasks, including dialog generation, machine translation, and abstractive summarization. Without using any extra labeled data or introducing additional model parameters, our method significantly outperforms strong baselines.

Recommended citation: Shufang Xie, Ang Lv, Yingce Xia, Lijun Wu, Tao Qin, Tie-Yan Liu, Rui Yan, Target-Side Input Augmentation for Sequence to Sequence Generation, International Conference on Learning Representations, 2022
