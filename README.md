# Multilayer perceptron mnist

Python algorithm uses backward propagation and gradient decent.


We download [Mnist dataset](https://en.wikipedia.org/wiki/MNIST_database) as 8x8 matrix, which gives as 64 lenght vector. To get best parameters we split dataset on train, valid and test sets.


Activation function: `f(s) = 1/1+e^(-s)`


Starting values of weights and bias are taken from interval:
`(-1/sqrt(n); 1/sqrt(n))`

## Required libraries
- pandas
- numpy
- math
- copy