Deep Learning from Scratch using NumPy – Comparison with PyTorch

This project implements a deep learning framework from scratch using NumPy, focusing on manual forward and backward propagation without relying on automatic differentiation. The XOR dataset is used to evaluate model behavior and learning dynamics.

Overview
The project aims to build a fully functional neural network using NumPy and compare its training behavior with an equivalent implementation in PyTorch. The comparison highlights differences in training speed, stability, and implementation complexity.

Methodology
The neural network is implemented using manual matrix operations for forward propagation and explicit gradient calculations for backward propagation. Stochastic Gradient Descent with momentum is used for optimization. Two NumPy models are evaluated: one with Batch Normalization and one without it. A PyTorch model using autograd is implemented for comparison.

Experiments and Analysis
Training stability and convergence are analyzed using loss and accuracy curves. The impact of Batch Normalization on convergence speed and stability is clearly demonstrated. The PyTorch implementation shows faster convergence due to automatic differentiation and optimized computation.

Results

NumPy with Batch Normalization converges faster and more smoothly than the version without it

Manual NumPy implementation provides strong conceptual understanding but is computationally slower

PyTorch achieves the fastest and most stable training performance

Tools and Technologies
Python
NumPy
PyTorch
Matplotlib
Jupyter Notebook

Project Files

DeepLearning_From_Scratch_NumPy_vs_PyTorch.ipynb

DeepLearning_From_Scratch_Report.pdf

How to Run
Open the Jupyter Notebook file and run the cells sequentially.

Purpose
This project was built to understand the internal mechanics of deep learning models and compare manual implementations with modern deep learning frameworks.

Author
Albatul Altoum