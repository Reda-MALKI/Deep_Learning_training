Neural Network from Scratch with NumPy

A fully functional neural network implemented from scratch using only NumPy, without relying on deep learning frameworks like TensorFlow or PyTorch. This project demonstrates the core mechanics of neural networks, including forward and backward propagation, gradient descent, and loss computation, applied to the MNIST and Fashion MNIST datasets.

📖 Project Overview

This repository contains a Python implementation of a feedforward neural network built from the ground up using NumPy. The network is designed to classify images from the MNIST (handwritten digits) and Fashion MNIST (clothing items) datasets. The project serves as an educational tool to understand the inner workings of neural networks, from layer transformations to gradient-based optimization.

🔍 Key Features

Input Layer: 784 neurons (flattened 28×28 pixel images)

Hidden Layer: 128 neurons with ReLU activation

Output Layer: 10 neurons (for 10 classes, digits 0–9 or fashion items) with Softmax activation

He Initialization: Ensures better convergence by scaling initial weights appropriately

Mini-batch Gradient Descent: Optimizes training efficiency and convergence

Custom Implementations: Forward propagation, backward propagation, and cross-entropy loss

No Deep Learning Frameworks: Built entirely with NumPy for maximum transparency

📊 Results

MNIST Accuracy: 93.3% on the test set

Fashion MNIST Accuracy: 83.67% on the test set

The lower accuracy on Fashion MNIST reflects its increased complexity compared to MNIST, as clothing items have more varied patterns and textures.
