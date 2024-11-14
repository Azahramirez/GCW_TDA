# GCW TDA

To run the code is necessary to install the libraries detailed on Requirements.txt on a python env. For
the experiments python 3.10.14 was used

## 1Datageneration
This notebook shows how to create sample data with diferent SNR values (r parameter)

## 2ExplorationFS.ipynb

On this notebook the wave data is analyzed and gets transformed into the frequency domain using the FFT

## 3TDAExploration.ipynb

Here is presented the methodology to calculate a persistence diagram of the data, which can be transformed to an image

## 4ML_Models_Fourier.ipynb

This notebook generates the persistance image of the Fourier Transform of the waves and also tries different ML methods to predict if the wave is a GW or noise only using the Fourier transform.

## 5Convolutional_TDA.ipynb

In this notebook we generate a CNN to predict whether the persistance image of the FFT of a wave is related to a GW or just noise