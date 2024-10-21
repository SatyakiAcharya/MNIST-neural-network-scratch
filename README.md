# 🧠 MNIST Neural Network from Scratch
## Overview
This project demonstrates how to build a Neural Network from scratch to classify handwritten digits from the MNIST dataset without using any deep learning frameworks like TensorFlow or PyTorch. The neural network is entirely built using NumPy for matrix operations and Matplotlib for visualizations. The goal is to implement key components of a neural network, including forward propagation, backpropagation, and activation functions such as ReLU and Softmax.

## 🛠 Key Features
- No Deep Learning Frameworks: The entire neural network, including forward propagation, backpropagation, and gradient descent, is implemented from scratch using pure Python and NumPy.
- Custom Activation Functions: Implemented activation functions like ReLU (Rectified Linear Unit) and Softmax for hidden layers and output layer, respectively.
- MNIST Dataset: Uses the famous MNIST dataset of handwritten digits for training and testing.
- Basic Visualizations: Matplotlib is used to visualize the loss during training and sample predictions.

## 🧠 Neural Network Architecture
The implemented neural network consists of:

- Input Layer: Takes the 28x28 pixel MNIST images (flattened to 784 nodes).
- Hidden Layers: One hidden layers with ReLU activation functions.
- Output Layer: 10 output nodes (representing digits 0-9) with Softmax activation to provide probabilities for each class.

## 📊 Data
The MNIST dataset contains 60,000 training images and 10,000 testing images of handwritten digits (0-9), with each image represented as a 28x28 grayscale image. These images are flattened into vectors of 784 elements before being fed into the neural network.
