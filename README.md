# MNIST-Digit-Classification
Deep Learning assignment using TensorFlow/Keras for handwritten digit classification.

# MNIST Handwritten Digit Classification

## Overview

This project implements a simple neural network using TensorFlow/Keras
to classify handwritten digits from 0 to 9 using the MNIST dataset.

## Dataset

The MNIST dataset contains:

- 60,000 training images
- 10,000 testing images
- 28 × 28 grayscale images
- 10 digit classes (0–9)

## Model Architecture

The neural network consists of:

- Flatten layer
- Dense layer with 128 neurons and ReLU activation
- Dense layer with 64 neurons and ReLU activation
- Dense output layer with 10 neurons and Softmax activation

## Training

- Optimizer: Adam
- Loss function: Sparse Categorical Crossentropy
- Epochs: 10
- Batch size: 32
- Validation split: 10%

## Experiment

An additional experiment was performed by adding Dropout layers
with a dropout rate of 0.2.

The original model and dropout model were compared using test
accuracy and validation performance.

## Files

- `MNIST_Digit_Classification.ipynb` - Jupyter/Google Colab notebook
- `MNIST_Report.pdf` - Handwritten assignment report
- `digit_0.png` to `digit_4.png` - Handwritten test images
