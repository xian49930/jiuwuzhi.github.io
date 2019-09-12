---
layout:     post
title:      "Terms of Machine Learning - basic"
subtitle:   "\"\""
date:       2019-09-12
author:     XL
header-img: 
catalog: 	 true
tags:
    - Terminology
    - Machine Learning
    - Data Science
---

### Glossary of Machine Learning


- **batch or mini-batch**: training is always performed on batches of training data and labels. Doing so helps the algorithm converge. The "batch" dimension is typically the first dimension of data tensors. For example a tensor of shape [100, 192, 192, 3] contains 100 images of 192x192 pixels with three values per pixel (RGB).

- **cross-entropy loss**: a special loss function often used in classifiers.

- **dense layer**: a layer of neurons where each neuron is connected to all the neurons in the previous layer.

- **features**: the inputs of a neural network are sometimes called "features". The art of figuring out which parts of a dataset (or combinations of parts) to feed into a neural network to get good predictions is called "feature engineering".

- **labels**: another name for "classes" or correct answers in a supervised classification problem

- **learning rate**: fraction of the gradient by which weights and biases are updated at each iteration of the training loop.

- **logits**: the outputs of a layer of neurons before the activation function is applied are called "logits". The term comes from the "logistic function" a.k.a. the "sigmoid function" which used to be the most popular activation function. "Neuron outputs before logistic function" was shortened to "logits".

- **loss**: the error function comparing neural network outputs to the correct answers

- **neuron**: computes the weighted sum of its inputs, adds a bias and feeds the result through an activation function.

- **one-hot encoding**: class 3 out of 5 is encoded as a vector of 5 elements, all zeros except the 3rd one which is 1.

- **relu**: rectified linear unit. A popular activation function for neurons.

- **sigmoid**: another activation function that used to be popular and is still useful in special cases.

- **softmax**: a special activation function that acts on a vector, increases the difference between the largest component and all others, and also normalizes the vector to have a sum of 1 so that it can be interpreted as a vector of probabilities. Used as the last step in classifiers.

- **tensor**: A "tensor" is like a matrix but with an arbitrary number of dimensions. A 1-dimensional tensor is a vector. A 2-dimensions tensor is a matrix. And then you can have tensors with 3, 4, 5 or more dimensions.