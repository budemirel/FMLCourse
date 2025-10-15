# 🧠 Fundamentals of Machine Learning (FMLCourse)

**Author:** Burak Demirel  
**Title:** MRI Clinical Scientist  
**Company:** Philips Healthcare  

---

## 📘 Overview

This repository — **FMLCourse** — contains a series of interactive Python and PyTorch notebooks designed to teach and visualize core principles in **machine learning** and **optimization**.  
Each module provides an intuitive, hands-on demonstration of how algorithms learn, converge, and make decisions, from manual gradient descent to modern deep learning frameworks.

---

## 🚀 Contents

### 1. 🧩 **Gradient Descent Surface GUI**
- **File:** `gradient_descent_gui.py`  
- **Description:**  
  An interactive Tkinter-based visualization showing gradient descent in action on common objective functions such as Rosenbrock, Himmelblau, and quadratic surfaces.  
  Users can adjust the learning rate, gradient noise, and start point to visualize the optimization path in both **3D surface** and **2D contour** plots.

---

### 2. 🧠 **Two Moons — PyTorch MLP Trainer (GUI)**
- **File:** `two_moons_pytorch_gui.py`  
- **Description:**  
  A real-time PyTorch-powered trainer for the classic *Two Moons* dataset.  
  Uses automatic differentiation and built-in optimizers to train an MLP interactively.  
  The GUI allows you to modify hyperparameters, data noise, and architecture depth while watching the decision boundary evolve live.

---

### 3. ⚙️ **Two Moons — Manual Backpropagation (From Scratch GUI)**
- **File:** `two_moons_manual_backprop_gui.py` *(or similar)*  
- **Description:**  
  Implements forward and backward propagation **entirely from scratch** using NumPy — no PyTorch or autograd.  
  Every gradient and update step is computed manually, providing a transparent look at the mechanics behind neural network learning.

---

### 4. 📊 **Two Moons — PyTorch Training Script (Non-GUI)**
- **File:** `two_moons_pytorch_train.py`  
- **Description:**  
  A clean, non-interactive PyTorch training script for the *Two Moons* dataset.  
  Focuses on reproducible model training, validation, and visualization of **decision boundaries**, **loss curves**, and **accuracy trends**.

---

## 🧰 Requirements

All scripts use standard scientific Python libraries:

```bash
pip install numpy matplotlib torch
pip install tkinter
