# 🧠 Deep Learning — Neural Networks & CNNs

This module explores how deep learning models learn to recognize complex patterns through layered computations.  
We built both **fully connected Neural Networks (NNs)** and **Convolutional Neural Networks (CNNs)**.

---

## 🔹 Part 1: Neural Networks (NN)
- Implemented a **Sequential model** using `Dense` layers.
- Activation functions used:
  - `relu` → introduces non-linearity.
  - `softmax` → outputs probability distribution for classification.
- Learned about:
  - **Epochs** → number of full training passes through the data.
  - **Training vs Validation Accuracy** → to detect under/overfitting.
- Achieved **100% test accuracy** on the penguin dataset.

---

## 🔹 Part 2: Convolutional Neural Networks (CNN)
- Used **Conv2D** and **MaxPooling2D** layers to process image data (e.g. MNIST digits).
- Steps:
  1. Convolution layers learned basic shapes and textures.
  2. Pooling reduced dimensionality while keeping key features.
  3. Flattened the 2D maps into a 1D vector.
  4. Dense layers handled classification logic.
- Achieved **1.00 test accuracy**.
- Visualized **feature maps** (layer activations) to understand what each layer “sees”.

---

## 🧩 Key Libraries
- `tensorflow` / `keras`
- `numpy`
- `matplotlib`

---

## 📊 Next Up
Next module: **05_Projects** — applying ML and DL models to real-world datasets.
