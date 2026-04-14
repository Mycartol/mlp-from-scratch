# MLP from Scratch (NumPy)

## 📌 Overview
This project implements a **multilayer perceptron (MLP) from scratch using only NumPy**, without deep learning frameworks such as TensorFlow or PyTorch.

The goal was to understand and implement the full machine learning pipeline, including forward pass, backpropagation, and optimization.

---

## 📊 Dataset
- UCI Echocardiogram dataset
- ~130 medical records
- Binary classification problem (survival prediction)

---

## ⚙️ Key Features
- Fully manual implementation of:
  - Forward propagation
  - Backpropagation
  - Gradient descent optimization
- Momentum-based learning optimization
- Data preprocessing (normalization, train/test split)
- Stratified k-fold cross-validation (k=5)
- Hyperparameter experimentation (>20 configurations)

---

## 📈 Results
- MLP model accuracy: ~80–85%
- Logistic Regression (baseline): ~60%
- Significant performance improvement on non-linear patterns

---

## 🔍 Key Takeaways
- Demonstrates understanding of neural network internals
- Shows impact of hyperparameters on generalization
- Validates advantage of non-linear models over linear baseline

---

## 🛠 Tech Stack
Python, NumPy, Scikit-learn, Matplotlib
