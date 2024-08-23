# Neural Network Backpropagation Example

This script demonstrates a basic implementation of a neural network with backpropagation using Python. It consists of a feedforward neural network with two output neurons and includes code for backpropagation to update the weights and biases.

## Overview

The script initializes random weights and biases and uses the sigmoid activation function to compute the outputs of the neural network. It then performs backpropagation to calculate the error gradients and adjust the weights and biases to minimize the error.

### Key Functions

- **sigmoid(x)**: Computes the sigmoid activation function.
- **sigmoid_derivative(x)**: Computes the derivative of the sigmoid function, used for backpropagation.

### Neural Network Architecture

The neural network consists of:

- Input layer with 2 neurons (a, b)
- Hidden layer with 3 neurons (x, y, z)
- Another hidden layer with 3 neurons (p, q, r)
- Output layer with 2 neurons (o1, o2)

### Training Process

1. **Initialization**: Weights and biases are initialized randomly.
2. **Forward Pass**: The inputs are passed through the network to compute the outputs.
3. **Error Calculation**: The difference between the predicted and actual outputs is calculated.
4. **Backpropagation**: The gradients of the error with respect to each weight and bias are computed, and the weights and biases are updated accordingly.

### How to Run

To run this script, you need to have Python installed on your machine. You can execute the script from the command line or any Python IDE. 

```bash
python neural_network.py
Output
The script prints the updated weights and biases after each iteration of training.

Requirements
Python 3.x
No additional libraries are required as the script uses only built-in Python modules.

License
This project is licensed under the MIT License - see the LICENSE file for details.
