---
layout: post
author:
  name: Team NNFL
  email: bitsnnfl@gmail.com
share: true
title: "[ID-11]-Deep Subspace Clustering Networks"
categories:
- CNN
- Autoencoders
- Decoders
tags: []

---
**Abstract -** We present a novel deep neural network architecture for unsupervised subspace clustering. This architecture is built upon deep auto-encoders, which non-linearly map the input data into a latent space. Our key idea is to introduce a novel self-expressive layer between the encoder and the decoder to mimic the “selfexpressiveness” property that has proven effective in traditional subspace clustering. Being differentiable, our new self-expressive layer provides a simple but effective way to learn pairwise affinities between all data points through a standard backpropagation procedure. Being nonlinear, our neural-network based method is able to cluster data points having complex (often nonlinear) structures. We further propose pre-training and fine-tuning strategies that let us effectively learn the parameters of our subspace clustering networks. Our experiments show that our method significantly outperforms the state-of-the-art unsupervised subspace clustering techniques.