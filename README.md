# Deep Neural Network from Scratch (NumPy)

This notebook provides a hands-on, step-by-step implementation of deep neural networks using NumPy. The primary goal is to illustrate the power of network depth by comparing a shallow neural network against a deeper one, both designed to have a comparable total number of parameters.

---

## 🔍 What's Inside
* Generation of a synthetic binary classification dataset.
* Implementation of core activation functions: Sigmoid and ReLU, along with their derivatives.
* Detailed, explicit forward propagation for both shallow and deep architectures.
* Layer-by-layer backpropagation for gradient computation.
* Parameter updates via gradient descent.
* Comparison of a shallow network ([20, 256, 1]) against a deep network ([20, 64, 64, 64, 64, 1]).
* Visualization of the cost over training iterations to compare learning performance.
* Final accuracy evaluation for both models.

---

## 🎯 Why This Project
This project highlights a fundamental concept in deep learning: the importance of network depth. By implementing both a shallow and a deep neural network, with the same number of neurons, and trained with the same hyperparameters, you can intuitively grasp how deeper architectures can be more effective at learning complex patterns and relationships in data. It solidifies understanding of data flow, gradient propagation, and parameter updates within multi-layered networks.

---

## 📓 Notebook 
[Open the notebook](./Deep%20NN%20from%20Scratch.ipynb)
