# Neural-networks-from-scratch
# Neural Network from Scratch using XOR Gate

## Overview
This project demonstrates the implementation of an **Artificial Neural Network (ANN) from scratch** using Python and NumPy without relying on deep learning frameworks such as TensorFlow or PyTorch. The neural network is trained and tested on the **XOR (Exclusive OR) gate**, a classic non-linear problem that cannot be solved using a single-layer perceptron. The project covers the complete implementation of forward propagation, backpropagation, weight updates using gradient descent, and performance evaluation.

## Features
- Implementation of a Neural Network from scratch
- XOR gate classification
- Random weight and bias initialization
- Forward propagation
- Sigmoid activation function
- Backpropagation algorithm
- Gradient descent optimization
- Loss calculation during training
- Prediction and testing on XOR inputs

## Technologies Used
- Python
- NumPy
- Matplotlib (for loss visualization, if included)
- Google Colab / Jupyter Notebook

## Dataset
This project uses the XOR truth table as the training dataset.

| Input 1 | Input 2 | Output |
|---------|---------|--------|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

## Model Architecture
- Input Layer (2 Neurons)
- Hidden Layer
- Sigmoid Activation Function
- Output Layer (1 Neuron)

## Workflow
1. Import required libraries
2. Define the XOR dataset
3. Initialize weights and biases
4. Implement the sigmoid activation function
5. Perform forward propagation
6. Compute the loss
7. Perform backpropagation
8. Update weights using gradient descent
9. Train the neural network
10. Test the trained model on XOR inputs

## Installation

```bash
pip install numpy
pip install matplotlib
```

## How to Run
1. Clone the repository.
2. Install the required dependencies.
3. Open the notebook in Google Colab or Jupyter Notebook.
4. Run all cells sequentially.
5. Observe the training process, loss reduction, and final XOR predictions.

## Expected Output

| Input | Predicted Output |
|--------|------------------|
| (0, 0) | ≈ 0 |
| (0, 1) | ≈ 1 |
| (1, 0) | ≈ 1 |
| (1, 1) | ≈ 0 |

## Applications
- Understanding Neural Networks
- Learning Backpropagation
- Machine Learning Fundamentals
- Deep Learning Foundations
- Educational Demonstration of XOR Classification

## Future Improvements
- Support for multiple hidden layers
- Different activation functions (ReLU, Tanh)
- Mini-batch gradient descent
- Adam optimizer implementation
- Multi-class classification
- Training on real-world datasets

## Author
Developed as a Deep Learning project to understand the fundamentals of Artificial Neural Networks by implementing a neural network from scratch and solving the XOR gate classification problem.
