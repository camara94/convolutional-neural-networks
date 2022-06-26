# Convolutional Neural Networks

Implement the foundational layers of CNNs (pooling, convolutions) and stack them properly in a deep network to solve multi-class image classification problems.

## Learning Objectives

* Explain the convolution operation
* Apply two different types of pooling operations
* Identify the components used in a convolutional neural network (padding, stride, filter, ...) and their purpose
* Build a convolutional neural network
* Implement convolutional and pooling layers in numpy, including forward propagation
* Implement helper functions to use when implementing a TensorFlow model
* Create a mood classifer using the TF Keras Sequential API
* Build a ConvNet to identify sign language digits using the TF Keras Functional API
* Build and train a ConvNet in TensorFlow for a binary classification problem
* Build and train a ConvNet in TensorFlow for a multiclass classification problem
* Explain different use cases for the Sequential and Functional APIs

## Computer Vision Problems

![image](images/1.png)

![image](images/2.png)

## Vertical Edge Detection

![image](images/3.png)
![image](images/4.png)
![image](images/5.png)

## Vertical Edget

![image](images/6.png)

## Learning to detect edgets

![image](images/7.png)

## Get Specific Edgets 

![image](images/8.png)

## Padding Image

![image](images/9.png)

## Valid And Same Convolutions
Valid: 
* nxn * fxf -> n-f+1  x n-f+1 
* 6x6 * 3x3 -> 4x4

![image](images/11.png)

## Strided Convolution

![image](images/12.png)

## Strided Formula 

![image](images/13.png)

## Summary Of Convoultion

![image](images/14.png)

## Technical Note On Cross-correlation vs. Convolution

## Convolution In Math Textbook

![image](images/15.png)

## Convolutions On RGB Images

![image](images/16.png)

![image](images/17.png)

![image](images/18.png)

## Multiple Filters

![image](images/19.png)

![image](images/20.png)

## Example Of A Layer

![image](images/22.png)

## Exercise

![image](images/23.png)

## Summary Of Convolution

![image](images/24.png)

## Pooling Layer: Max pooling

![image](images/25.png)

## Summary of MaxPooling

![image](images/26.png)

![image](images/27.png)

## Number of Parameters

![image](images/28.png)

Here are the 5 typos:

1. 208 should be (5*5*3 + 1) * 8 = 608
2. 416 should be (5*5*8 + 1) * 16 = 3216
3.  In the FC3, 48001 should be 400*120 + 120 = 48120, since the bias should have 120 parameters, not 1
4.  Similarly, in the FC4, 10081 should be 120*84 + 84 (not 1) = 10164

(Here, the bias is for the fully connected layer.  In fully connected layers, there will be one bias for each neuron, so the bias become In FC3 there were 120 neurons so 120 biases.)

5. Finally, in the softmax, 841 should be 84*10 + 10 = 850

## Why Use Convolution

![image](images/29.png)

![image](images/30.png)

This is based on the equation:

![image](images/31.png)

## Outline

![image](images/32.png)

## LeNet-5

![image](images/34.png)

## AlexNext

![image](images/35.png)

## VGG-16
![image](images/36.png)


## Residual block

![image](images/37.png)

## Residual Network

![image](images/38.png)

![image](images/39.png)

![image](images/40.png)

![image](images/41.png)

![image](images/42.png)

## The Problem of computational cost

![image](images/43.png)

## 1X1 Convolution

![image](images/44.png)

## Inception Module

![image](images/46.png)

## Inception Network

![image](images/48.png)

## Origin Inception

[https://knowyourmeme.com/memes/we-need-to-go-deeper](https://knowyourmeme.com/memes/we-need-to-go-deeper)

## Mobile Net

![image](images/49.png)

![image](images/55.png)

![image](images/50.png)

![image](images/51.png)

![image](images/52.png)

![image](images/53.png)

![image](images/54.png)

![image](images/56.png)

![image](images/57.png)

![image](images/58.png)

![image](images/60.png)

![image](images/61.png)

![image](images/63.png)

![image](images/64.png)

![image](images/65.png)

![image](images/66.png)

## Common Augmentation Method

### 1. Mirroring

![image](images/67.png)

### 2. Random Cropping

![image](images/69.png)

### 3. Color Shifting

![image](images/70.png)

## Implementing Distortions During Training

![image](images/71.png)

## Object Localization

### Defining the target label y

![image](images/72.png)

![image](images/73.png)

![image](images/74.png)