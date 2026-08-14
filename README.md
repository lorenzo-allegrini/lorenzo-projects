# lorenzo-projects

# MNIST Neural Network from Scratch:

A four-layer neural network built from scratch with NumPy to classify handwritten digits from Kaggle’s Digit Recognizer dataset.

This project implements the full training process without machine-learning frameworks: forward propagation, backpropagation, ReLU activation, softmax classification, gradient descent, hyperparameter optimisation, model checkpointing, and Kaggle submission generation.

## Model architecture
The network contains four layers:

- Input layer: 784 pixel features from a 28 × 28 grayscale image
- Hidden layer 1: configurable number of neurons with ReLU activation
- Hidden layer 2: configurable number of neurons with ReLU activation
- Output layer: 10 neurons with softmax activation for digits 0–9

### Dataset
Kaggle Digit recogniser. 


# Housing_ML_Pipeline:
An end-to-end machine-learning project predicting California housing prices.

## Contents
- Built preprocessing pipelines for missing values, scaling, encoding, and feature engineering.
- Compared Linear Regression, Decision Tree, Random Forest, Ridge, and Gradient Boosting.
- Tuned Ridge and Gradient Boosting with 5-fold cross-validation.
- Best model: Gradient Boosting, achieving test R² of 0.812.
### Dataset
California Housing dataset.
