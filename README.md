# Neural Networks

## Repository containing various Neural Network projects created using Keras, Tensorflow, SKLearn. List and summary of projects are below:

##1. Predicting House Prices:

This is an expansion of a project from the Medium Article (below). Updated the code base and added seeding to the Keras and SKLearn models in order to create reproducable results during training.

Build your first Neural Network to predict house prices with Keras:
https://medium.com/intuitive-deep-learning/build-your-first-neural-network-to-predict-house-prices-with-keras-eb5db60232c

The project creates three different models:

1. Three layered Neural Net used to predict housing prices.
2. Regularized Network with multiple additional layers and high Neuron count to simulate Overfitting.
3. Neural Net which introduces L2_Regularization and Dropout as ways of resolving Overfitting issues.

##2. Convolution Neural Network

This project is also an expansion on the second part to the above Medium Article:

https://medium.com/intuitive-deep-learning/intuitive-deep-learning-part-2-cnns-for-computer-vision-24992d050a27

Demonstrates how to create a Convolution Neural network which is used for image recognition. Demonstrates how to load and normalize image data using Keras, set up the output to fit the classification recognition task, and set up the various layers of the CNN as specified below:

Conv Layer (Filter size 3x3, Depth 32)
Conv Layer (Filter size 3x3, Depth 32)
Max Pool Layer (Filter size 2x2)
Dropout Layer (Prob of dropout 0.25)
Conv Layer (Filter size 3x3, Depth 64)
Conv Layer (Filter size 3x3, Depth 64)
Max Pool Layer (Filter size 2x2)
Dropout Layer (Prob of dropout 0.25)
FC Layer (512 neurons)
Dropout Layer (Prob of dropout 0.5)
FC Layer, Softmax (10 neurons) 
