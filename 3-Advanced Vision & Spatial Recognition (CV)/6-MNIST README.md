# 👁️ Advanced CNN Vision: Digit Recognizer

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=for-the-badge&logo=tensorflow)
![Streamlit](https://img.shields.io/badge/Deployment-Streamlit-red?style=for-the-badge&logo=streamlit)
![Accuracy](https://img.shields.io/badge/Kaggle_Accuracy-99.56%25-brightgreen?style=for-the-badge)

## 📌 Overview
This repository contains an industrial-grade Convolutional Neural Network (CNN) pipeline designed for high-precision image classification. The model has been meticulously trained, evaluated, and deployed as a real-time interactive web application.

Achieving a top-tier **99.56% accuracy**, this project demonstrates a complete Computer Vision workflow from raw data processing to live MLOps deployment.

## 🚀 Live Inference Deployment
The trained neural network is fully deployed. You can draw a digit on the canvas and test the model's real-time prediction capabilities directly from your browser:

👉 **[TEST THE LIVE MODEL HERE](https://huggingface.co/spaces/Ironside35/Advanced-Digit-Recognizer)** 👈

## 🧠 Architecture & Engineering Standards
* **Core Model:** Deep Convolutional Neural Network (CNN)
* **Optimization Techniques:** * Maximized Feature Engineering via Data Augmentation
  * Stable training loops using Batch Normalization
  * Dynamic Learning Rate Reduction and Dropout mechanisms to eliminate overfitting
* **Inference Engine:** TensorFlow/Keras backend integrated with a Streamlit frontend.

## ⚙️ Repository Structure
* `app.py`: The Streamlit application script for the web interface.
* `mnist_cnn_model.h5`: The exported, production-ready model weights.
* `requirements.txt`: Dependency list for cloud deployment.
