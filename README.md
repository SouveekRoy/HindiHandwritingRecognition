# MLProject-HindiHandwritingRecognition

## The data files are large so cannot be uploaded
For the data.csv file goto-https://drive.google.com/open?id=1YLL4gAWg6W_L9NNPSMhsv8J6Rq_lNWbI

For UCI Repository of Devanagari Hindi handwriting go to-https://archive.ics.uci.edu/ml/datasets/Devanagari+Handwritten+Character+Dataset\
Code Requirements
You can install Conda for python which resolves all the dependencies for machine learning.

# Description
### This code successfully recognizes hindi characters.

# Technique Used
### I have used convolutional neural networks. I am using Tensorflow as the framework and Keras API for providing a high level of abstraction.

# Architecture
## CONV2D --> MAXPOOL --> CONV2D --> MAXPOOL -->FC -->Softmax--> Classification
# Some additional points
### 1. You can go for additional conv layers.
### 2. Add regularization to prevent overfitting.
### 3. You can add additional images to the training set for increasing the accuracy.
# Python Implementation
## 1. Dataset- DHCD (Devnagari Character Dataset)
## 2. Images of size 32 X 32
## 3. Convolutional Network Support added.
# Train Acuracy ~ 95%
# Test Acuracy ~ 92%

