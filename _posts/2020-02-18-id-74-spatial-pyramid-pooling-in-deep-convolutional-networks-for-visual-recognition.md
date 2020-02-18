---
layout: post
author:
  name: "74"
  email: bitsnnfl@gmail.com
share: true
title: Spatial Pyramid Pooling in Deep Convolutional Networks for Visual Recognition
categories:
- CNN
- Object Detection
- Image Classification
tags: []

---
**Abstract:** Existing deep convolutional neural networks (CNNs) require a fixed-size (e.g., 224×224) input image. This requirement is “artificial” and may reduce the recognition accuracy for the images or sub-images of an arbitrary size/scale. In this work, we equip the networks with another pooling strategy, “spatial pyramid pooling”, to eliminate the above requirement. The new network structure, called SPP-net, can generate a fixed-length representation regardless of image size/scale. Pyramid pooling is also robust to object deformations. With these advantages, SPP-net should, in general, improve all CNN-based image classification methods. On the ImageNet 2012 dataset, we demonstrate that SPP-net boosts the accuracy of a variety of CNN architectures despite their different designs. On the Pascal VOC 2007 and Caltech101 datasets, SPP-net achieves state-of-the-art classification results using a single full-image representation and no fine-tuning. The power of SPP-net is also significant in object detection. Using SPP-net, we compute the feature maps from the entire image only once, and then pool features in arbitrary regions (sub-images) to generate fixed-length representations for training the detectors. This method avoids repeatedly computing the convolutional features. In processing test images, our method is24-102×faster than the R-CNN method, while achieving better or comparable accuracy on Pascal VOC 2007.

**Conference:** ECCV 2014

**Dataset:** VOC 2007, ILSVRC 2014

**Task:**

1. Implement the model on Tensorflow and Keras
2. Implement the proper data loader with any 2 data augmentation techniques.
3. Use subsets for paper implementation. Clearly report the number of data samples of each category in training and testing sets.