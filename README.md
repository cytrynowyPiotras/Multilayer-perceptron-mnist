# Multilayer perceptron mnist

Python algorithm uses backward propagation and gradient decent.


We download [the Mnist dataset](https://en.wikipedia.org/wiki/MNIST_database) as an 8x8 matrix, which gives a 64-length vector. To get the best parameters, we split the dataset into train, valid, and test sets.


Activation function: `f(s) = 1/1+e^(-s)`


Starting values of weights and bias are taken from interval:
`(-1/sqrt(n); 1/sqrt(n))`

## Required libraries
- pandas
- numpy
- math
- copy
