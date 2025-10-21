# 🧠 Fundamentals of Machine Learning (FMLCourse)

**Author:** Burak Demirel  
**Title:** MRI Clinical Scientist  
**Company:** Philips Healthcare  

---

## 📘 Overview

This repository — **FMLCourse** — contains a series of interactive Python and PyTorch notebooks designed to teach and visualize core principles in **machine learning** and **optimization**.  
Each module provides an intuitive, hands-on demonstration of how algorithms learn, converge, and make decisions — from manual gradient descent to modern deep learning architectures like convolutional neural networks.

---

## 🚀 Contents

### 1. 🧩 **Gradient Descent Surface GUI**
- **File:** `how_to_gradient_descent.ipynb`  
- **Description:**  
  An interactive Tkinter-based visualization showing gradient descent in action on common objective functions such as Rosenbrock, Himmelblau, and quadratic surfaces.  
  Users can adjust the learning rate, gradient noise, and start point to visualize the optimization path in both **3D surface** and **2D contour** plots.

---

### 2. 🧠 **Two Moons — PyTorch MLP Trainer (GUI)**
- **File:** `how_to_train.ipynb`  
- **Description:**  
  A real-time PyTorch-powered trainer for the classic *Two Moons* dataset.  
  Uses automatic differentiation and built-in optimizers to train an MLP interactively.  
  The GUI allows you to modify hyperparameters, data noise, and architecture depth while watching the decision boundary evolve live.

---

### 3. ⚙️ **Two Moons — Manual Backpropagation (From Scratch GUI)**
- **File:** `how_to_train.ipynb` *(or similar)*  
- **Description:**  
  Implements forward and backward propagation **entirely from scratch** using NumPy — no PyTorch or autograd.  
  Every gradient and update step is computed manually, providing a transparent look at the mechanics behind neural network learning.

---

### 4. 📊 **Two Moons — PyTorch Training Script (Non-GUI)**
- **File:** `how_to_train.ipynb`  
- **Description:**  
  A clean, non-interactive PyTorch training script for the *Two Moons* dataset.  
  Focuses on reproducible model training, validation, and visualization of **decision boundaries**, **loss curves**, and **accuracy trends**.

---

### 5. 📸 **Convolutional Neural Networks — Filters, Feature Maps & Training (GUI)**
- **File:** `how_to_CNN.ipynb`  
- **Description:**  
  An intuitive, interactive notebook introducing **Convolutional Neural Networks (CNNs)** from the ground up.  
  Demonstrates:
  - A **PyTorch training pipeline** for classifying MNIST digits with live plots of accuracy and loss.  
  Includes both **conceptual visualization** and **hands-on CNN training**

---

### 6. 🧼 **U-Net Denoising — on MNIST**
- **File:** `how_to_CNN.ipynb`
- **Description:**  
  A demonstration of **image denoising** using a **U-Net architecture** trained in a **supervised** manner.  
  Implements:
  - Real-time visualization of noisy vs. denoised digits.  
  - Validation using **PSNR/MSE** metrics.  
  - Optional checkpoint saving, visualization tools, and comparison with supervised baselines.  

---

## 🧰 Requirements

All scripts use standard scientific Python libraries:

```bash
pip install numpy matplotlib torch
pip install tkinter
