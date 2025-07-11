# Neural Network from Scratch

## Overview

This repository contains implementations of a 3-layer deep neural network for nonlinear regression using various frameworks, including NumPy, PyTorch, TensorFlow, and TensorFlow Lite. The assignment emphasizes building the networks from scratch where applicable, avoiding built-in layers where required, and using advanced tensor operations such as `einsum` instead of matrix multiplication. Additionally, all implementations are accompanied by explanations of the code and results.

## Repository Structure

The repository includes multiple Colab notebooks, each implementing a different variant of the deep neural network:

### **1. NumPy Implementation (From Scratch)**

- Implements a 3-layer deep neural network for nonlinear regression using NumPy.
- Includes proper non-linear activation functions and hidden layers.
- Manual backpropagation and gradient computation using the chain rule.
- **Colab Link:** [NumPy from Scratch](https://colab.research.google.com/drive/1TAH--F-BPfpOKQPjwmS8dCLv9CQ4Hzyt?usp=sharing)

### **2. PyTorch Implementations**

#### a) PyTorch from Scratch (Without Built-in Layers)

- Implements a 3-layer deep neural network without using PyTorch's built-in layer functions.
- **Colab Link:** [PyTorch Scratch](https://colab.research.google.com/drive/13CTpk8uSXmYW6db1KDuZE1WTWo3UYOhp?usp=sharing)

#### b) PyTorch Using Modules

- Implements a structured version of the network using PyTorch’s `nn.Module`.
- **Colab Link:** [PyTorch with Modules](https://colab.research.google.com/drive/1ylvxcPxoruiWnh8yG5XdITeQWP6aQJ0Z?usp=sharing)

#### c) PyTorch Lightning Version

- Implements the same network using PyTorch Lightning for better training management.
- **Colab Link:** [PyTorch Lightning](https://colab.research.google.com/drive/1zPdsKXbiueZZNccplCbJcB1D0YMXYIDr?usp=sharing)

### **3. TensorFlow Implementations**

#### a) TensorFlow from Scratch (Without High-Level API)

- Implements the 3-layer network manually in TensorFlow, avoiding high-level APIs.
- Uses `einsum` instead of traditional matrix multiplication.
- **Colab Link:** [TensorFlow Scratch](https://colab.research.google.com/drive/1P1XSXPQiiKNyoFZ4JRCKKMhQ05quFGU1?usp=sharing)

#### b) TensorFlow Built-in Layers

- Implements the same network using TensorFlow’s `Dense` layers.
- **Colab Link:** [TensorFlow Built-in](https://colab.research.google.com/drive/17_m8ihquumIK238dQPoBsBaX293IJxuR?usp=sharing)

#### c) TensorFlow Functional API

- Uses TensorFlow’s Functional API to implement the network.
- **Colab Link:** [Functional API](https://colab.research.google.com/drive/1gcEYA1rW0Hx0PzU39w_iCokWyYuaKgIp?usp=sharing)

### **4. 4D Plot of Synthetic Data**

- The dataset is generated using a 3-variable nonlinear equation.
- The data is plotted using Matplotlib in a 4D visualization.
- **Reference:** [4D Plot Guide](https://colab.research.google.com/drive/1u8z0B8gr6vQ3lxXfV4cH4xD2SMpXPev6?usp=sharing)

## Execution Instruction

1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd <repo-name>
   ```
2. Open and run the Colab notebooks following the links provided.
3. Follow the inline comments and markdown explanations in each notebook.

## Video Walkthrough
- A detailed walkthrough of the executed Colab notebooks is available.
- **Video Link:** [YT video](https://youtu.be/-uZOeIojGpI)

---

