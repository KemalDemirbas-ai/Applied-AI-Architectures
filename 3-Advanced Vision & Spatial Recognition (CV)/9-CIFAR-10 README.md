<div align="center">

<img src="https://img.icons8.com/nolan/128/artificial-intelligence.png" width="120" alt="AI Engine Logo">

# 👁️ Autonomous Vision System (CIFAR-10)
**End-to-End Convolutional Neural Network & MLOps Pipeline**

[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)](https://streamlit.io/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

<br>

### 🚀 [CLICK HERE TO LAUNCH THE LIVE AI APPLICATION](https://huggingface.co/spaces/Ironside35/CIFAR10-Autonomous-Vision?logs=container)

*The model is fully deployed on Hugging Face Spaces. Click the link above to upload your own images and test the neural engine in real-time.*

</div>

---

## 📋 Executive Summary
This project showcases the development and deployment of a custom **Deep Convolutional Neural Network (CNN)**. Engineered entirely from scratch, the system autonomously classifies raw images into 10 distinct categories using the benchmark CIFAR-10 dataset. Moving beyond traditional local execution, this project bridges the gap between model training and production deployment through modern **MLOps** practices.

<div align="center">
  <img src="https://storage.googleapis.com/tfds-data/visualization/fig/cifar10-3.0.2.png" alt="CIFAR-10 Samples" width="600">
</div>

---

## 🧠 Core Architecture & Neural Engine
The deep learning pipeline is designed for maximum feature extraction and generalization without relying on pre-trained models (Transfer Learning). 

**Strategic Highlights:**
- **Data Augmentation:** Synthetic visual diversity (rotations, flips, zooms) to prevent network overfitting.
- **Batch Normalization:** Applied across convolutional blocks to ensure gradient stability and accelerate convergence.
- **Dynamic Learning Rate:** Utilized `ReduceLROnPlateau` for precision tuning when the validation loss plateaus.
- **Short-circuit Logic:** Optimized Python inference script with zero `if/else` statements for rapid image preprocessing.

### Supported Classifications:
`Airplane` | `Automobile` | `Bird` | `Cat` | `Deer` | `Dog` | `Frog` | `Horse` | `Ship` | `Truck`

---

## ⚙️ MLOps & Deployment (Phase 4)
This repository proves that the model does not just exist in a Jupyter Notebook. The serialized brain (`.h5`) has been integrated into a lightweight web application.

- **Frontend:** Streamlit 
- **Cloud Hosting:** Hugging Face Spaces
- **Preprocessing:** Autonomous 32x32 resizing, RGBA to RGB conversion, and pixel normalization handled at the inference level.



