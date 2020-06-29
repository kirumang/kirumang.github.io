---
title: "Unsupervised Domain Adaptation through Inter-modal Rotation for RGB-D Object Recognition"
collection: publications
permalink: /publication/2020-04-RelativeRotation
excerpt: "<img src='/images/RelativeRotation_main.jpg'>"
date: 2020-06-23
venue: 'RA-L'
paperurl: 'https://arxiv.org/abs/2004.10016'
authors: 'Mohammad Reza Loghmani, Luca Robbiano, Mirco Planamente, <b>Kiru Park</b>, Barbara Caputo, and Markus Vincze'
---

Unsupervised Domain Adaptation (DA) exploits the supervision of a label-rich source dataset to make predictions on an unlabeled target dataset by aligning the two data distributions. In robotics, DA is used to take advantage of automatically generated synthetic data, that come with "free" annotation, to make effective predictions on real data. However, existing DA methods are not designed to cope with the multi-modal nature of RGB-D data, which are widely used in robotic vision. We propose a novel RGB-D DA method that reduces the synthetic-to-real domain shift by exploiting the inter-modal relation between the RGB and depth image. Our method consists of training a convolutional neural network to solve, in addition to the main recognition task, the pretext task of predicting the relative rotation between the RGB and depth image. To evaluate our method and encourage further research in this area, we define two benchmark datasets for object categorization and instance recognition. With extensive experiments, we show the benefits of leveraging the inter-modal relations for RGB-D DA.

[Download paper](https://arxiv.org/abs/2004.10016)

