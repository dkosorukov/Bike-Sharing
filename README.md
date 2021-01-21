# Bike-Sharing
Use a neural network to predict daily bike rental ridership.

## Project Components
Package includes a Jupyter Notebook and my_answers.py that contains NeuralNetwork class loaded to the notebook.
The data comes from the [UCI Machine Learning Database](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset)

## Packages
Project uses python 3, numpy, pandas, matplotlib, jupyter nootebook

## Neural Network description
Numpy is used to do network's initialization, training (pass forward and backpropogation). Network includes input and output layers. The hidden layer uses Sigmoid function for activation.

myanswers.py file has the network hyperparameters:

- nubmer of iterations
- learning rate
- number of hidden nodes
- number of output nodes

Reasonably good results (validation loss of 0.149) are observed at iterations of 4000, learning rate of 1.2, and the number of the hidden nodes of 7.

## License
myanswers.py is a public domain work, dedicated using [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Feel free to do whatever you want with it.
