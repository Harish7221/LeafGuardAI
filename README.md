# 🌿 LeafGuardAI

LeafGuardAI is a CNN-based leaf disease detection system designed to help farmers identify plant diseases early and accurately by analyzing leaf images.

---

## 🚀 Overview

Plant diseases like **Early Blight** and **Late Blight** can severely reduce crop yield if not detected early.  
LeafGuardAI uses a trained **Convolutional Neural Network (CNN)** model to classify leaf images and predict whether the plant is **Healthy**, affected by **Early Blight**, or **Late Blight**.

The project focuses on **simplicity, accuracy, and real-world usability** for farmers.

---

## 🛠 Tech Stack

- **Python**
- **TensorFlow / Keras**
- **Convolutional Neural Networks (CNN)**
- **Flask** (Backend API)
- **OpenCV**
- **HTML, CSS, JavaScript**
- **Git & GitHub**

---

## ✨ Features

- Upload plant leaf images
- Classifies leaves into:
  - Healthy
  - Early Blight
  - Late Blight
- Fast and accurate predictions using a trained CNN model
- Simple and farmer-friendly workflow

---

## 🧠 How It Works

1. User uploads a leaf image through the interface
2. Image is preprocessed (resizing, normalization)
3. CNN model analyzes the image
4. Model predicts the disease class
5. Result is displayed to the user

---

## 📂 Project Structure

```text
LeafGuardAI/
├── potato_disease/        # Model training / backend logic
├── potatoes.h5            # Trained CNN model
├── models.config.example  # Model configuration
├── README.md
├── .gitignore
└── .gcloudignore


