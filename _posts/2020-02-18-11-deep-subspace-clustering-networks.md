---
layout: post
author:
  name: 'Paper ID: 11'
  email: bitsnnfl@gmail.com
share: true
title: Deep Subspace Clustering Networks
categories:
- CNN
- Autoencoders
- Decoders
tags: []

---
**Abstract -** We present a novel deep neural network architecture for unsupervised subspace clustering. This architecture is built upon deep auto-encoders, which non-linearly map the input data into a latent space. Our key idea is to introduce a novel self-expressive layer between the encoder and the decoder to mimic the “self-expressiveness” property that has proven effective in traditional subspace clustering. Being differentiable, our new self-expressive layer provides a simple but effective way to learn pairwise affinities between all data points through a standard backpropagation procedure. Being nonlinear, our neural-network based method is able to cluster data points having complex (often nonlinear) structures. We further propose pretraining and fine-tuning strategies that let us effectively learn the parameters of our subspace clustering networks. Our experiments show that our method significantly outperforms the state-of-the-art unsupervised subspace clustering techniques.

Paper: [https://arxiv.org/abs/1709.02508](https://arxiv.org/abs/1709.02508 "https://arxiv.org/abs/1709.02508")

**Tasks :** 

1. Implement the CNN model discussed in the paper.
2. Implement the proper dataloader with any 2 data augmentation techniques.
3. Implement the model in three parts:
   * Encoder
   * Self Expressive layer in Between
   * Decoder
4. Use the datatsets and training strategy mentioned in paper.

**Datasets :** It is recommended to use the dataset mentioned in 4.3(you have to train it on a single dataset).