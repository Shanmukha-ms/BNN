# Binary Neural Network (BNN) with PyTorch

This repository contains the implementation of a Binary Neural Network (BNN) using PyTorch, trained on the MNIST dataset. BNNs significantly reduce memory usage and computational complexity by binarizing weights and activations, making them ideal for deployment on resource-constrained devices.

## Introduction

Binary Neural Networks (BNNs) are a type of neural network where the weights and activations are constrained to binary values, typically -1 and +1. This repository provides a step-by-step implementation of BNNs, including key techniques like the Straight-Through Estimator (STE) for training.

## Installation

To run the code in this repository, you'll need Python and PyTorch installed on your system. Follow the instructions below to set up your environment:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/bnn-pytorch.git
    cd bnn-pytorch
    ```

2. Create a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install torch
    ```
## Network Architecture

The network consists of:

	•	An input layer of size 784 (for 28x28 pixel images)
	•	Three hidden layers of sizes 500, 400, and 300
	•	An output layer of size 10 (for the 10 digit classes)

Only the second and third hidden layers are binarized.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

