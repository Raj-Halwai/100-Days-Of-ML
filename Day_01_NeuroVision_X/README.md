NeuroVision-X 🧠

Deep Artificial Neural Network From Scratch for Multi-Class Brain MRI Classification

Author

Raj Halwai

Objective

To build a Deep Artificial Neural Network completely from scratch using Python and NumPy for classifying Brain MRI images into four distinct disease categories.

Dataset

The dataset contains 7,200 Brain MRI images divided into training (5,600) and testing (1,600) sets across 4 classes:

Glioma

Meningioma

Pituitary

No Tumor

Architecture & System Design

Input: Flattened array of size (12,288) representing 64x64x3 RGB images.

Layers: Dense(1024, ReLU) → Dense(512, ReLU) → Dense(256, ReLU) → Softmax(4)

Loss Function: Categorical Cross-Entropy with L2 Regularization

Optimization: Mini-Batch Gradient Descent with Exponential Learning Rate Decay

Technologies & Stack

Python

NumPy

OpenCV

Matplotlib

Pandas

Scikit-Learn (for metrics and dataset splitting only)

Deep Learning Frameworks Used

None. Everything is implemented mathematically from scratch, including:

Forward Propagation

Backpropagation (calculating gradients for weights and biases manually)

He Initialization (Crucial for deep ReLU networks)

Categorical Cross-Entropy Loss
