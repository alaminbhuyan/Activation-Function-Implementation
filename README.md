# Activation Functions in Deep Learning

## Table of Contents
- [Introduction](#introduction)
- [Significance of Activation Functions](#significance-of-activation-functions)
- [Types of Activation Functions](#types-of-activation-functions)
  - [Sigmoid](#sigmoid)
  - [Hyperbolic Tangent (tanh)](#hyperbolic-tangent-tanh)
  - [Rectified Linear Unit (ReLU)](#rectified-linear-unit-relu)
  - [Leaky ReLU](#leaky-relu)
  - [Parametric ReLU (PReLU)](#parametric-relu-prelu)
  - [Exponential Linear Unit (ELU)](#exponential-linear-unit-elu)
  - [Scaled Exponential Linear Unit (SELU)](#scaled-exponential-linear-unit-selu)
  - [Softmax](#softmax)
  - [Swish Activation Function](#SwishActivationFunction)
- [Conclusion](#conclusion)

## Introduction

In deep learning, an activation function is a mathematical operation applied to the output of a node or neuron in a neural network. It introduces non-linearity to the model, enabling it to learn complex patterns and relationships in the data.

## Significance of Activation Functions

Activation functions serve two main purposes in a neural network:

1. **Introducing Non-Linearity:** Without activation functions, a neural network would behave like a linear model, making it incapable of learning from and adapting to complex, non-linear relationships present in real-world data.

2. **Enabling Model Training:** Activation functions help in training deep neural networks by allowing the model to backpropagate errors and adjust weights during the optimization process.

## Types of Activation Functions

### Sigmoid

The sigmoid function squashes input values to the range (0, 1), making it suitable for binary classification problems.

### Hyperbolic Tangent (tanh)

Similar to the sigmoid, tanh squashes input values to the range (-1, 1), providing zero-centered outputs and mitigating issues related to vanishing gradients.

### Rectified Linear Unit (ReLU)

ReLU is one of the most widely used activation functions. It outputs the input for positive values and zero for negative values, introducing non-linearity and simplicity to the model.

### Leaky ReLU

Leaky ReLU allows a small, positive gradient for negative input values, preventing dead neurons and addressing the "dying ReLU" problem.

### Parametric ReLU (PReLU)

PReLU is an extension of Leaky ReLU, where the slope of the negative part is learned during training rather than being fixed.

### Exponential Linear Unit (ELU)

ELU aims to mitigate the dying ReLU problem by allowing negative values with a smooth transition, and it has been shown to improve learning dynamics.

### Scaled Exponential Linear Unit (SELU)

SELU is a self-normalizing activation function that can maintain mean activation values close to 0 and standard deviations close to 1 during training, leading to improved network performance.

### Softmax

Softmax is often used in the output layer for multi-class classification problems. It converts raw scores into probability distributions over multiple classes.

### Swish Activation Function


## Conclusion

Understanding and choosing the right activation function is crucial for the success of a neural network. Experimentation and consideration of the specific characteristics of your data and task are essential in making informed decisions.
