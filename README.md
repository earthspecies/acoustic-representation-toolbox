# Acoustic Representation Toolbox

## Introduction

What is the best representation of audio for machine learning and neural networks?

Applying machine learning techniques to acoustic data often requires extensive feature engineering: All representations of audio have benefits and drawbacks. For example, raw audio minimizes the number of preprocessing assumptions and lets the neural nets get as close to the data as possible, but can be challenging to work with because understanding audio requires spanning many orders of magnitude in time. Understanding the different between "fast" and "vast" requires millisecond nuance, but understanding "former" in "Of whales and humans, whose voice more powerfully carries? With conversations over hundreds of killometers, it is the former," requiries a thousands of milliseconds.  Conventionally, it is common to compute a STFT-based spectrogram, yielding 2D "image" outputs that can be fed into a convolution neural network (CNN). However, spectrogram based approaches force a trade-off between the time resolution and frequency resolution.

This is why we made the Acoustic Representation Toolbox. There are numerous ways to represent audio, and here we explore a few. This is a live toolbox—we are constantly adding and refining representations—and is a work in progress.

1. Time and frequency domain representations
1. Spectrograms
1. Hilbert-Huang transforms 
1. Continuous wavelet transforms
1. Spectral hyperresolution representations
1. Miscellaneous representations
1. Deep-learned representations (constructed via generative models) 

Each of these methods is introduced and detailed in a tutorial-style module that provides theoretical background in concert with practical application. Our mission for this toolbox is to construct a relatively comprehensive set of representation tools in order to be able to optimize the acoustic feature engineering process prior to training a machine learning model.
