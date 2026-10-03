THIS IS NOT ORIGINAL WORK 

THIS HAS BEEN COPIED FROM ANDREJ KARPATHY AND SHOULD BE CONSIDERED AS A LEARNING EXERCISE DONE BY ME

# Micrograd From Scratch

A small scalar-valued automatic differentiation engine and
neural network library built from scratch in Python.

## What I implemented

- Scalar Value objects
- Automatic differentiation
- Backpropagation
- Addition, subtraction, multiplication and division
- Powers
- tanh, exp and ReLU
- Neurons
- Layers
- Multi-layer perceptrons
- Parameter collection
- Gradient descent
- XOR training example

## Example

2 → 4 → 4 → 1 MLP

trained on XOR:

(0,0) → 0
(0,1) → 1
(1,0) → 1
(1,1) → 0

## Goal

The goal of this project was to understand automatic
differentiation, computational graphs and neural networks
by implementing the core components from scratch rather
than relying on PyTorch autograd.