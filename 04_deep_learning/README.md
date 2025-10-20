# 🧠 Deep Learning

This section introduces the fundamentals of **Deep Learning**, starting with Artificial Neural Networks (ANNs).

---

## 📘 Contents
| Notebook | Description |
|-----------|-------------|
| `neural_networks.ipynb` | Implementation of a simple feedforward neural network using TensorFlow/Keras |
| `cnn_intro.ipynb` | (Next) Intro to Convolutional Neural Networks for image data |

---

## 🌱 What You’ll Learn
- The intuition behind **neurons**, **layers**, and **activations**
- How neural networks learn through **backpropagation**
- The difference between **train**, **validation**, and **test** data
- Understanding metrics like **accuracy**, **loss**, and **epochs**
- Why Deep Learning is part of Machine Learning, but distinct from traditional ML

---

## 🧩 Neural Network Architecture Overview

- **Input Layer:** Takes the features (e.g., penguin measurements)
- **Hidden Layers:** Learn patterns and combinations of features
- **Output Layer:** Predicts the final class (species)
- **Activation Functions:**
  - `ReLU` → For hidden layers, introduces non-linearity
  - `Softmax` → For output layer in classification problems

---

## 📊 Example Result (from `neural_networks.ipynb`)

```
Accuracy: 1.0
Confusion Matrix:
[[19 0 0]
[ 0 13 0]
[ 0 0 13]]
```

✅ Perfect accuracy — the neural net successfully classified all penguins.

---

## 🚀 Next Step
Up next: **Convolutional Neural Networks (CNNs)**  
You’ll move from structured (table) data → image data, learning how CNNs detect edges, shapes, and patterns automatically.

---

### 🪴 Progress Tracker

| Stage | Status | Notes |
|--------|---------|--------|
| Neural Networks | ✅ Done | Built and trained a simple ANN |
| CNNs | ⏳ Next | Learn image-based deep learning |

### 🧠 Deep Learning Subtopics

- [Neural Networks (ANNs)](neural_networks.ipynb) – Understanding layers, activation functions, and backpropagation  
- [Convolutional Neural Networks (CNNs)](cnn_intro.ipynb) – Learn image classification with deep learning  


