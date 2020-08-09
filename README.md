# BikeSharePredictions

Project Overview

The data comes from the UCI Machine Learning Database.

https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset

## Dataset and Attributes

Assessing Data
This dataset has the number of riders for each hour of each day from January 1 2011 to December 31 2012. The number of riders is split between casual and registered, summed up in the cnt column. 


## Building the Network  

The network has two layers, a hidden layer and an output layer. The hidden layer will use the sigmoid function for activations. The output layer has only one node and is used for the regression, the output of the node is the same as the input of the node. That is, the activation function is  𝑓(𝑥)=𝑥 . A function that takes the input signal and generates an output signal, but takes into account the threshold, is called an activation function. We work through each layer of our network calculating the outputs for each neuron. All of the outputs from one layer become inputs to the neurons on the next layer. This process is called forward propagation.

I will be using the weights to propagate signals forward from the input to the output layers in a neural network. I will use the weights to also propagate error backwards from the output back into the network to update our weights. This is called backpropagation.

I have the following tasks:

- Implement the sigmoid function to use as the activation function. Set self.activation_function in init to your sigmoid function.
- Implement the forward pass in the train method.
- Implement the backpropagation algorithm in the train method, including calculating the output error.
- Implement the forward pass in the run method.
