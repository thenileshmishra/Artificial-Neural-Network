Basic Artificial Neural Network (ANN) Implementation

This project implements a simple Artificial Neural Network (ANN) from scratch in Python for binary classification using forward and backward propagation.

Features

Uses a synthetic dataset (make_moons) for binary classification.

Implements a feedforward neural network with:

Input layer: 2 neurons

Hidden layer: 4 neurons (sigmoid activation)

Output layer: 1 neuron (sigmoid activation)

Implements Binary Cross-Entropy loss function.

Trains the model using Gradient Descent.

Prints the loss every 10 epochs over 100 epochs.

No external deep learning libraries like TensorFlow or PyTorch are used.

Requirements

Python 3.x

NumPy

Scikit-learn

You can install the required dependencies using:

pip install numpy scikit-learn

How to Run

Ensure all dependencies are installed.

Run the script:

python ann_forward_backward.py

The model will train and print loss values at every 10 epochs.

Files

ann_forward_backward.py - Contains the ANN implementation.

README.md - This documentation.

Output Example

Epoch 0, Loss: 0.6932
Epoch 10, Loss: 0.4856
Epoch 20, Loss: 0.3754
...
Epoch 90, Loss: 0.2678

Notes

The dataset is standardized before training.

Weights and biases are initialized randomly.

The learning rate is set to 0.1, but it can be tuned for better performance.

References

Scikit-learn documentation: https://scikit-learn.org/stable/

Neural Networks and Deep Learning by Michael Nielsen: http://neuralnetworksanddeeplearning.com/


