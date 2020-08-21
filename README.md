# Acoustic Representation Toolbox

## Introduction

Applying machine learning (ML) techniques to acoustic data typically requires extensive feature engineering since it is not always feasible to input long sequences of raw audio data into neural networks. Conventionally, it is common to compute a STFT-based spectrogram, yielding 2D "image" outputs that can be fed into a convolution neural network (CNN). However, there are numerous alternatives, and here we explore a few. While this repo is still a work in progress, at the moment we consider (1) time and frequency domain representations, (2) spectrograms, (3) Hilbert-Huang transforms, (4) continuous wavelet transforms, (5) spectral hyperresolution representations, (6) miscellaneous representations, and (7) deep-learned representations constructed via generative models. 

Each of these methods is introduced and detailed in a tutorial-style module that provides theoretical background in concert with practical application. Our mission for this toolbox is to construct a relatively comprehensive set of representation tools in order to be able to optimize the acoustic feature engineering process prior to training a ML model.