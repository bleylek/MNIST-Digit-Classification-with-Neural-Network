# MNIST Digit Classification with Neural Network

This repository contains a notebook for classifying handwritten digits from the MNIST dataset using a neural network. The project demonstrates the entire workflow, from loading the dataset to evaluating the model's performance.

## Project Overview

The goal of this project is to classify images of handwritten digits (0-9) using a neural network. The notebook covers the following steps:

1. **Data Loading and Preprocessing**: The MNIST dataset is loaded, and the images are normalized to improve the performance of the neural network.

2. **Model Building**: A simple feedforward neural network is built using Keras, a high-level neural networks API. The model architecture consists of an input layer, two hidden layers with ReLU activation, and an output layer with sigmoid activation.

3. **Model Training**: The model is trained on the training set using categorical cross-entropy loss and the Adam optimizer. Training accuracy and loss are monitored to ensure the model is learning effectively.

4. **Model Evaluation**: After training, the model is evaluated on the test set to measure its accuracy. The evaluation metrics are printed, and some predictions are visualized to assess the model's performance.

5. **Prediction Example**: The notebook includes an example of making a prediction with the trained model, where it predicts the digit of a new handwritten image.

## Results

The trained neural network achieves high accuracy on the MNIST test set. The model is capable of correctly classifying the majority of handwritten digits.
