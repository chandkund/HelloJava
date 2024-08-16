# PyTorch Fundamentals
This project provides a foundational introduction to PyTorch, focusing on the basics of tensors, their creation, manipulation, and operations, which are essential for understanding and building deep learning models.
## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Code Explanation](#code-explanation)

## Project Overview

This project demonstrates key concepts and operations related to PyTorch tensors, such as creating tensors, performing tensor operations like addition, multiplication, matrix multiplication, reshaping, and more. These fundamentals form the basis for more advanced deep learning applications.


## Installation

To run this project, you will need Python along with the following libraries:

- `numpy`
- `torch`
- `pandas`
- `matplotlib`

Install the required packages using `pip`:

```bash
pip install torch numpy pandas matplotlib
```
## Usage
To explore the fundamentals of PyTorch:

Ensure that you have the required libraries installed.
Run the code snippets to experiment with tensor operations
```python
import torch
# Creating a tensor
tensor = torch.tensor([1, 2, 3])
print(tensor)
```
## Code Explanation
- **Introduction to Tensors**:
Tensors: The basic building block in PyTorch, similar to arrays in NumPy.
Random Tensors: Used as initial weights in neural networks, important for model training.
- **Creating Tensors**:
Scalar, Vector, Matrix: Demonstrates how to create different types of tensors.
Random Tensors: Explanation of their importance in neural networks.
- **Tensor Operations**:
Addition, Subtraction, Multiplication: Basic arithmetic operations on tensors.
Matrix Multiplication: A key operation in deep learning, along with rules for valid multiplication.
Reshaping, Stacking, Squeezing, Unsqueezing: Operations to change tensor dimensions and shapes.
- **Tensor Attributes**:
Data Type, Shape, Device: How to access and manipulate tensor properties.
- **Tensor Aggregation**:
Min, Max, Mean, Sum: Operations to aggregate tensor data.
-**Tensor Manipulation**:
View, Permute: Techniques to change tensor shape without altering the underlying data.





