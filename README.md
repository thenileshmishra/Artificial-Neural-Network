# Basic Artificial Neural Network (ANN) Implementation

This project implements a simple **Artificial Neural Network (ANN)** from scratch in Python for **binary classification** using forward and backward propagation.

---

## 🚀 Features

- Uses a **synthetic dataset** (`make_moons` from Scikit-learn) for binary classification.
- Implements a **feedforward neural network** with:
  - **Input layer**: 2 neurons  
  - **Hidden layer**: 4 neurons (with **sigmoid activation**)  
  - **Output layer**: 1 neuron (with **sigmoid activation**)  
- Utilizes **Binary Cross-Entropy** loss function.
- Trains the model using **Gradient Descent**.
- Displays the loss **every 10 epochs** over **100 epochs**.
- **No external deep learning libraries** like TensorFlow or PyTorch are used.

---

## 📦 Requirements

Ensure you have **Python 3.x** installed, along with the following dependencies:

- `numpy`
- `scikit-learn`

Install them using:

```sh
pip install numpy scikit-learn
