# Neural Networks: Simulating a perceptron class

In this project, we implement a **Perceptron** model — one of the simplest types of artificial neural networks — to solve a basic binary classification task. The perceptron, introduced by Frank Rosenblatt in 1958, is a foundational concept in machine learning that demonstrates how a model can learn to classify data points using a linear decision boundary.

## Project Overview

The project includes the following key components:

### 1. Perceptron Class
The `Perceptron` class is implemented to:
- Initialize the model with input dimensions and weights.
- Compute the **weighted sum** of inputs using a linear combination of weights and features.
- Apply an **activation function** to determine the output.
- **Train** the perceptron using a basic weight update rule.

### 2. Training Data
We use a predefined dataset called `small_training_set`. The dataset consists of 2D input points and their corresponding binary target values (`1` or `-1`):
