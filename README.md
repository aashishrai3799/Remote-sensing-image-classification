# Remote-sensing-image-classification
classification of remote sensing images using Convolutional Neural Networks (CNN)

#### Dataset used: RSI-CB (A Large Scale Remote Sensing Image Classification Benchmark via Crowdsource Data)

## Introduction
Remote sensing is the acquisition of information about an object or phenomenon without making physical contact with the object
and thus in contrast to on-site observation, especially the Earth.
In this model supervised method of image classification is used for classifying remote sensing images. Experiments were carried out on the
dataset provided and has been tested against different test images.

## Working
The Tensorflow model is build using a Convolutional Neural Network(CNN), and is trained using 8 different classes of RSI-CB
dataset. Hence, it is able to classify images into 8 different classes. The input to the model is a ?x64x64x3 RGB-image-vector,
and output is a ?x8 vector. Each row of the output vector corresponds to a different class.

Train accuracy: 87.7%

Test accuracy: 84.8%

#### Platform: Python 3.7

## Libraries
*   numpy      - 1.16
*   matplotlib - 3.0.3
*   tensorflow - 1.14
*   PIL        - 4.3.0
*   tqdm
*   pyunpack
*   urllib
*   time
*   os
*   math


#### I trained the model on Tesla T4 GPU and took around 11 seconds for 5 epochs.

##### NOTE: Contact if you get HTTP error while downloading RSI-CB dataset
