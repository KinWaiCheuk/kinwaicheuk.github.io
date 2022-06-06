---
title: "Latent Space Representation for Multi-Target Speaker Detection and Identification with a Sparse Dataset Using Triplet Neural Networks"
collection: publications
permalink: /publication/Latent_Triplet
excerpt: ''
date: 2020-02-20
venue: 'Automatic Speech Recognition and Understanding Workshop (ASRU)'
---
We present an approach to tackle the speaker recognition problem using Triplet Neural Networks. Currently, the i-vector representation with probabilistic linear discriminant analysis (PLDA) is the most commonly used technique to solve this problem, due to high classification accuracy with a relatively short computation time. In this paper, we explore a neural network approach, namely Triplet Neural Networks (TNNs), to built a latent space for different classifiers to solve the Multi-Target Speaker Detection and Identification Challenge Evaluation 2018 (MCE 2018) dataset. This training set contains i-vectors from 3,631 speakers, with only 3 samples for each speaker, thus making speaker recognition a challenging task. When using the train and development set for training both the TNN and baseline model (i.e., similarity evaluation directly on the i-vector representation), our proposed model outperforms the baseline by 23%. When reducing the training data to only using the train set, our method results in 309 confusions for the Multi-target speaker identification task, which is 46% better than the baseline model. These results show that the representational power of TNNs is especially evident when training on small datasets with few instances available per class.

[Download](https://ieeexplore.ieee.org/abstract/document/9003922)