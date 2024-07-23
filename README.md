# Multiclass classification using a pretrained neural network

## Main goal
Make multiclass classification model using pretrained Neural Network

## Data description

Primary dataset consists of 2 folders - train, valid; each of them contains 5 folders with pictures of celebrities: Elon Mask, Bill Gates, Jeff Bezos, Mark Zuckerberg, Steve Jobs. 

## Metric

Main metric used - accuracy.

## Summary

Pretrained ResNet34 model with following modifications was used to achieve the goal:
* Last fully connected layer was replaced with new one with 5 outputs accordind to quantity of classes expected.
* Only last layer's weights were updated during the training procedure

<img src='data/Resnet-34-Architecture.png'>

As a result accuracy value more than 90% was achived on validation subset.

## Libraries & tools used
* see the requirements
