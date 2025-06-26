# 🧠 Neural Networks from Scratch

Welcome to the **Neural Networks from Scratch** project! This repository contains a comprehensive, ground-up implementation of a simple artificial neural network using only basic Python and NumPy—no high-level libraries like TensorFlow or PyTorch.

This project is intended for learners and enthusiasts who want to understand the fundamental building blocks of neural networks by **building everything from scratch**.

---

## 📚 Project Highlights

- ✅ **No external machine learning libraries** — only NumPy and Python
- 🏗️ **Custom implementation** of:
  - Forward propagation
  - Backward propagation
  - Loss computation (Mean Squared Error)
  - Weight and bias updates
- 📊 Simple synthetic dataset for demonstration
- 🔄 Fully interactive via Jupyter Notebook

---

## 🧾 Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Neural Network Architecture](#neural-network-architecture)
4. [Key Concepts](#key-concepts)
5. [Results](#results)
6. [Contributing](#contributing)
   
---

## 🔧 Installation

To get started, clone the repository and install the required dependencies:

```bash
git clone [https://github.com/your-username/neural-networks-from-scratch.git](https://github.com/Abhaykum123/Neural_Network_from_Scratch.git)
cd neural-networks-from-scratch
pip install -r requirements.txt  # Only NumPy is required
```

----

## ▶️ Usage
To run the notebook:
```
jupyter notebook Neural_Networks_from_Scratch.ipynb

```

Or open it directly in Google Colab for a one-click experience.

---
## 🧱 Neural Network Architecture
The current model has:

- Input layer: 2 neurons (for 2D inputs)

- Hidden layer: 3 neurons with sigmoid activation

- Output layer: 1 neuron with sigmoid activation

---

## 🔍 Key Concepts
- Manual forward pass

- Activation functions: Sigmoid

- Manual backpropagation with chain rule

- Gradient descent

- Loss function: Mean Squared Error (MSE)

---

## 📈 Results
The network is trained on a basic dataset (e.g., binary classification). After training, the model is able to approximate the target function with a good degree of accuracy.

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!<br>

Feel free to fork this repo and submit a pull request if you’d like to:

- Add new activation/loss functions

- Implement batch learning or optimizers

- Add visualization or logging tools

---
## 🙌 Acknowledgements
This project was inspired by educational content on neural networks and is aimed at reinforcing conceptual understanding by implementing every component from scratch.

