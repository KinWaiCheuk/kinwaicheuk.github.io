---
title: "nnAudio"
excerpt: "A GPU audio processing library based on PyTorch <br/>[<img src='/images/nnAudio.png' style='height: auto; width:50%;'>](https://github.com/KinWaiCheuk/nnAudio)"
date: 2019-09-02
collection: portfolio
---

[Github Repo](https://github.com/KinWaiCheuk/nnAudio)

nnAudio is an audio processing toolbox using PyTorch convolutional neural network as its backend. By doing so, spectrograms can be generated from audio on-the-fly during neural network training and the Fourier kernels (e.g. or CQT kernels) can be trained. [Kapre](https://github.com/keunwoochoi/kapre) has a similar concept in which they also use 1D convolutional neural network to extract spectrograms based on [Keras](https://keras.io).

Other GPU audio processing tools are [torchaudio](https://github.com/pytorch/audio) and [tf.signal](https://www.tensorflow.org/api_docs/python/tf/signal). But they are not using the neural network approach, and hence the Fourier basis can not be trained. As of PyTorch 1.6.0, torchaudio is still very difficult to install under the Windows environment due to `sox`. nnAudio is a more compatible audio processing tool across different operating systems since it relies mostly on PyTorch convolutional neural network. The name of nnAudio comes from `torch.nn`

## Installation
`pip install git+https://github.com/KinWaiCheuk/nnAudio.git#subdirectory=Installation`

or

`pip install nnAudio==0.3.1`

## Documentation
[https://kinwaicheuk.github.io/nnAudio/index.html](https://kinwaicheuk.github.io/nnAudio/index.html)