---
layout: post
share: true
title: 'SegNet: A Deep Convolutional Encoder-Decoder Architecture for Image Segmentation'
author:
  name: Tanay Agrawal
  email: f2015567@pilani.bits-pilani.ac.in
categories:
- Image Segmentation
tags:
- Medium
date: 2019-03-20 08:57:00 +0000

---
**Abstract:** We present a novel and practical deep fully convolutional neural network architecture for semantic pixel-wise segmentation termed SegNet. This core trainable segmentation engine consists of an encoder network, a corresponding decoder network followed by a pixel-wise classification layer. The architecture of the encoder network is topologically identical to the 13 convolutional layers in the VGG16 network \[1\]. The role of the decoder network is to map the low resolution encoder feature maps to full input resolution feature maps for pixel-wise classification. The novelty of SegNet lies is in the manner in which the decoder upsamples its lower resolution input feature map(s). Specifically, the decoder uses pooling indices computed in the max-pooling step of the corresponding encoder to perform non-linear upsampling. This eliminates the need for learning to upsample. The upsampled maps are sparse and are then convolved with trainable filters to produce dense feature maps. We compare our proposed architecture with the widely adopted FCN \[2\] and also with the well known DeepLab-LargeFOV \[3\], DeconvNet \[4\] architectures. This comparison reveals the memory versus accuracy trade-off involved in achieving good segmentation performance. SegNet was primarily motivated by scene understanding applications. Hence, it is designed to be efficient both in terms of memory and computational time during inference. It is also significantly smaller in the number of trainable parameters than other competing architectures and can be trained end-to-end using stochastic gradient descent. We also performed a controlled benchmark of SegNet and other architectures on both road scenes and SUN RGB-D indoor scene segmentation tasks. These quantitative assessments show that SegNet provides good performance with competitive inference time and most efficient inference memory-wise as compared to other architectures.

**Paper Link:** [https://arxiv.org/pdf/1511.00561.pdf](https://arxiv.org/pdf/1511.00561.pdf "https://arxiv.org/pdf/1511.00561.pdf")

1. Implement the architecture given in the paper preferably not in caffe.
2. Train the neural net using datasets mentioned in the paper.
3. Compare the results obtained with the given paper.

**ID:** 103