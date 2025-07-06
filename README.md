# Image-Classifier
# 😊 Deep CNN Image Classifier - Happy vs Sad Emotions

This is a simple deep learning project that uses a Convolutional Neural Network (CNN) to classify facial emotion images as either **Happy** or **Sad**. Built and trained using TensorFlow and Keras on Google Colab.

---

## 🧠 Features

- Binary classification (Happy vs Sad)
- Image preprocessing and corrupt image filtering
- CNN model with Conv2D, MaxPooling, Dense layers
- Visualizations for training and validation metrics
- Evaluation using precision, recall, and accuracy
- Upload and predict custom images via Colab
- TensorBoard integration for training insights

---
##  🚀 Model Architecture
Input: 256x256 RGB Image
↓
Conv2D → ReLU → MaxPooling
↓
Conv2D → ReLU → MaxPooling
↓
Conv2D → ReLU → MaxPooling
↓
Flatten → Dense (256) → ReLU
↓
Dense (1) → Sigmoid

## ⚙️ Installation

Run the project in Google Colab. Just follow these steps:

1. Upload your `Files.zip` (with `happy/` and `sad/` images inside).
2. Follow the Colab notebook step by step.

Install required packages:
```bash
!pip install --upgrade opencv-python matplotlib
