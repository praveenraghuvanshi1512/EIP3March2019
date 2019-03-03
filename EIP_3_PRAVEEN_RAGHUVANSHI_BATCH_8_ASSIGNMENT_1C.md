# EIP 3.0 - Assignment 1C

##### Praveen Raghuvanshi | Batch: 8 | praveenraghuvanshi@gmail.com

## Convolution

Convolution is the method of combining two functions to generate the third function. In neural networks, it's widely used for image recognition. A model is developed to identify objects in an image. Convolution Neural Network(CNN) involve multiple hidden layers for identifying patterns in an image. A general sequence of identifying the object in an image involves identifying Edges/Gradient followed by Texture followed by Patterns followed by Part of objects and finally an object. In convolution pixels are multiplied with weights and a sum is calculated to give output of hidden layer which determine a pattern/object

## Epochs

An epoch is a term used in deep neural networks. One epoch is a single pass through of a model across whole training set. It involves covering both forward and backward pass through. Number of epoch influence the efficiency of a model and may increase or decrease it. More the number of epochs, more time will be taken to execute a model. Time to complete an epoch increases as we increase the training set.

## 1x1 convolution

1x1 convolution is a technique used in deep neural network to modify the number of channels in a hidden layer.  There is no effect of 1x1 on other parameters. It allows extending  or shrinking of channels as per the need arises. Consider a case of an digit where no of classes is 10(0-9). We can apply 1x1 convolution to bring down the channels to 10.



## 3x3 convolution

3x3 convolution is used to identify various aspects of a image. It reduces the dimension and provide different patterns of a image. It is frequently used kernel as it's quite fast. A 2 times 3x3 convolution is around 1.4 times faster than a single 5x5 convolution and 3 times 3x3 is1.8 times faster than a single 7x7 convolution. However, its quite memory intensive compared to higher kernels. It reduces the dimension by 2.

## Activation Functions

An activation function defines outputs of a neuron for a given set of inputs. They are triggered as a result of response of a stimuli on a neuron. Real life problems are complex and need not be linear. Activation functions helps bringing non-linearity thereby improving accuracy of a model. Some of the commonly used activation functions as ReLU, Sigmoid, tanh etc. ReLU is most popular and allows values to be within 0 and 1. All negative values are transformed to zero.