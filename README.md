# General idea 

In this notebook the simple MLP was made from scratch using basic python libraries. MLP is then used as a  binary classifier. 

The process is as follows: 

1) Create class Value which saves information about the process of value calculation .This class is able to calculate gradients using the backward propagation. 
2) Create a Neuron Class which can proceed with input data using weights, biases and activation function. 
3) Organise Neurons in Layers - Layers can be a simple list of Neurons. 
4) Multilayer Perceptron can be organized as a list of Layers. 
5) Calculate a loss - e.g. it can be the sum of squared difference between predicted and true values.
6) Make a cycle which updates the values of weights and biases by adding to them a small portion of gradient with negative sign. 
7) Analyse the results of classification. 

#  Kudos 
This notebook was inspired by Andrej Karpathy and his "Neural Networks: Zero to Hero" https://karpathy.ai/zero-to-hero.html
