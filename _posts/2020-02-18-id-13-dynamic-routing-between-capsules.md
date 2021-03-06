---
layout: post
author:
  name: 'Paper ID: 13'
  email: bitsnnfl@gmail.com
share: true
title: Dynamic Routing Between Capsules
categories:
- CNN
tags: []

---
Abstract: A capsule is a group of neurons whose activity vector represents the instantiation parameters of a specific type of entity such as an object or an object part. We use the length of the activity vector to represent the probability that the entity exists and its orientation to represent the instantiation parameters. Active capsules at one level make predictions, via transformation matrices, for the instantiation parameters of higher-level capsules. When multiple predictions agree, a higher level capsule becomes active. We show that a discrimininatively trained, multi-layer capsule system achieves state-of-the-art performance on MNIST and is considerably better than a convolutional net at recognizing highly overlapping digits. To achieve these results we use an iterative routing-by-agreement mechanism: A lower-level capsule prefers to send its output to higher level capsules whose activity vectors have a big scalar product with the prediction coming from the lower-level capsule.

Paper: [https://arxiv.org/abs/1710.09829](https://arxiv.org/abs/1710.09829 "https://arxiv.org/abs/1710.09829")

Dataset: [http://www.cs.toronto.edu/\~tijmen/affNIST/](http://www.cs.toronto.edu/\~tijmen/affNIST/ "http://www.cs.toronto.edu/~tijmen/affNIST/")

Task:

1. Implement the architecture proposed in the paper(4)
2. Segmenting highly overlapping digits (6)

Section of the paper is mentioned for each task