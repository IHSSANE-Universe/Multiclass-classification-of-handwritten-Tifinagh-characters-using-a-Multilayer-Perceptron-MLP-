# Multiclass Classification of Handwritten Tifinagh Characters

##  Description

This project focuses on the classification of handwritten **Tifinagh characters** using a **Multilayer Perceptron (MLP)** implemented from scratch with **NumPy**.

The project uses the **Amazigh Handwritten Character Database (AMHCD)** and aims to classify handwritten characters into **33 classes**.

The neural network is implemented manually, including forward propagation, ReLU and Softmax activation functions, categorical cross-entropy, backpropagation, and parameter updates.

---

##  Objectives

- Classify handwritten Tifinagh characters into 33 classes.
- Implement an MLP from scratch using NumPy.
- Understand forward propagation and backpropagation.
- Preprocess and normalize images.
- Train the model using mini-batch gradient descent.
- Evaluate the model using different classification metrics.
- Experiment with L2 regularization, Adam, K-Fold Cross-Validation, and data augmentation.

---

##  Dataset

The project uses the **Amazigh Handwritten Character Database (AMHCD)**.

| Property | Value |
|---|---:|
| Number of classes | 33 |
| Original image size | 64 × 64 |
| Image type | Grayscale |
| Processed image size | 32 × 32 |
| Input features | 1024 |
| Classification | Multiclass |

### Preprocessing

The images are:

1. Converted to grayscale.
2. Resized from `64 × 64` to `32 × 32`.
3. Normalized to `[0, 1]`.
4. Flattened into vectors of `1024` features.

The dataset is divided into:

```text
60% Training
20% Validation
20% Test
