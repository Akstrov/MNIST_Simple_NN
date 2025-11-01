# MNIST Simple Neural Network

A simple implementation of a neural network for the MNIST handwritten digit classification task using PyTorch.

## Project Description

This project implements a basic neural network architecture to classify handwritten digits from the MNIST dataset. The network features:

- Two linear layers with ReLU activation in between
- Cross-entropy loss function with softmax
- PyTorch implementation

## Architecture

The neural network consists of:
1. Input layer (784 neurons - flattened 28x28 MNIST images)
2. First linear layer with ReLU activation
3. Second linear layer
4. Softmax layer (part of cross-entropy loss)

## Requirements

- Python 3.x
- PyTorch
- torchvision
- numpy

## Usage

The project is implemented in a Jupyter notebook (`MNIST_Simple_NN.ipynb`). To run the project:

1. Install the required dependencies
2. Open the Jupyter notebook
3. Run the cells sequentially to:
   - Load and preprocess the MNIST dataset
   - Create and train the neural network
   - Evaluate the model's performance

## Results

The model demonstrates the basics of deep learning by achieving reasonable accuracy on the MNIST dataset, serving as a good starting point for understanding neural networks and PyTorch implementation.

## License

This project is open source and available under the MIT License.
