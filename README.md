
# 📊 TensorFlow Demos – Tensors, Loss Functions, and Optimizer Comparison

This repository contains three educational TensorFlow-based Python scripts that demonstrate core deep learning concepts: tensor operations, loss function analysis, and optimizer comparison using the MNIST dataset.

---

## 📁 Files and Descriptions

### 1. **tensor\_operations.py**

This script performs fundamental operations on tensors in TensorFlow, including:

* Creating random tensors
* Reshaping and transposing tensors
* Broadcasting smaller tensors to match larger tensor shapes
  It includes printed shapes and a clear explanation of broadcasting rules.

### 2. **loss\_function\_comparison.py**

This script compares two important loss functions:

* **Mean Squared Error (MSE)**
* **Binary Cross-Entropy (BCE)**

It uses example predictions and visualizes how each loss function responds to changes in predicted values using a bar chart.

### 3. **mnist\_optimizer\_comparison.py**

A full training example on the MNIST digit classification dataset, comparing:

* **Adam optimizer**
* **Stochastic Gradient Descent (SGD)**

The models are trained for 5 epochs each, and validation accuracy is plotted across epochs to visualize performance differences.

---

## 📦 Requirements

To run the scripts, make sure you have the following Python packages installed:

```bash
pip install tensorflow matplotlib numpy
```

Or install via `requirements.txt` (if included).

---

## ▶️ How to Run

```bash
python tensor_operations.py
python loss_function_comparison.py
python mnist_optimizer_comparison.py
```

---

## 📈 Output

* Printed shapes and broadcasted tensors
* Loss values and bar chart comparisons
* Validation accuracy graph comparing Adam vs. SGD

---

## 📚 Learning Objectives

These scripts are designed to help beginners understand:

* Basic tensor manipulations in TensorFlow
* How different loss functions behave in binary classification
* The impact of optimizer selection in training deep neural networks

