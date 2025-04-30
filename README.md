# Real-Time Emotion Detection using CNN on FER-2013

A course project for *Machine Learning (EE524)* at IIT Guwahati under the guidance of **Dr. M.K. Bhuyan**, this project involves building a real-time emotion detection system using Convolutional Neural Networks (CNNs) trained on the FER-2013 dataset.

## 🚀 Overview

This project aims to classify facial expressions into emotions such as **Happy**, **Sad**, **Angry**, **Surprised**, etc., using deep learning techniques. It also supports **real-time inference** via webcam using **OpenCV** and **Gradio** for interactive demos.

## 📁 Dataset

- **FER-2013**: Facial Expression Recognition dataset provided by Kaggle.
- Contains ~35,000 grayscale images of 48x48 pixels labeled across 7 emotion classes.

## 📌 Features

- ✅ Addressed class imbalance using image augmentation and class weights.
- ✅ Built and trained custom CNN models including **VGG16** and **ResNet-50**.
- ✅ Deployed a real-time emotion detector for live video streams.
- ✅ Interactive demo interface using **Gradio**.
- ✅ Modular, clean, and reproducible code.

## 🧠 Model Architectures

- **Custom CNN**: Baseline CNN model trained from scratch.
- **VGG16**: Pretrained on ImageNet, fine-tuned on FER-2013.
- **ResNet-50**: Deep residual learning model with strong generalization.

## 🛠️ Tech Stack

- Python, TensorFlow, Keras, OpenCV
- Gradio for real-time demos
- Scikit-learn, NumPy, Matplotlib for preprocessing and evaluation

## 🧪 Training Highlights

- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Data Augmentation: Horizontal flip, rotation, zoom
- Evaluation: Accuracy, Confusion Matrix

## 📊 Results

| Model     | Accuracy |
|-----------|----------|
| Custom CNN| ~60%     |
| VGG16     | ~68%     |
| ResNet-50 | ~70%     |

> Note: Accuracy may vary based on training configuration.

## 🎮 Demo

Run the Gradio app:

```bash
python app.py
