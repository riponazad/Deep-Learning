# Deep-Learning: A beginner's course using PyTorch
Deep learning course for beginners. Step by step tutorial using PyTorch.
### 1. Introduction to tensor of pytorch (TP_00)

Get used to with the tensor, finding similarities with numpy, its operation especially autograd at the end.


### 2. Multilayer Perceptron in PyTorch (TP_01)

#### Goal
Learn the basics of PyTorch (PT) by working on an artificial classification problem where we will implement MLP in low level using autograd of pytorch so that you get proper insight.

#### Plan
In this tutorial we will create a set of synthetic data that we will use as an example problem.
Then we will create a MLP model and learn its parameters from the data. Finally we will visualize the different learning measures and the parameters of the model.

In a second part we will modify our data and adapt the hyper-parameters (e.g. number of hidden neurons) of our model to allow better classification.

In the next part we will use the basic functions of PT to understand our process and how PT works. But we will also mention the high level features and aids of PT that facilitate our tasks.

#### Requirements

Python >=3.5

Modules python:
- pytorch >=1.0
- numpy
- matplotlib

### 3. High level deep learning (TP_02)

#### Introduction

In the past lab we have used the low-level API of PyTorch to implement an MLP. We trained the model to fit a synthetic data set and we experimented with different batch sizes and learning rates.

In this lab we will use one of PyTorch high-level APIs: `torch.nn`. This time we will experiment on more complex and natural datasets: MNIST or Fashion-MNIST.


#### Objectives
- Learn to use the PyTorch `nn` API
- Build, train and use a simple MLP
- Analyse the some of the predictions and mistakes of the model
