# DL-Using-Keras

## What's Keras:
- A High level library for DL
- Keras runs on top of Theano and Tensor flow. 
- A deep learning model is one with more than one hidden layer. 

## Run Jupyter notebook

	jupyter notebook

## Summary
- A dense layer is a classic fully connected neural network layer : each input node is connected to each output node.

- When we compile our models we use either theano or TensorFlow under the hood for efficient numerical computations. 

-An intuitive explanation from an application standpoint is to note that in machine learning cross-entropy is used to predict class probabilities, and MSE to predict values. For example, to predict if a house will be bough by someone over 40 years or below 40 you use cross-entropy. But if you try to predict the age of the buyer, you use MSE