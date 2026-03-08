
# 🫁 PneumoVision AI: Deep Learning Chest X-Ray Analysis
**A Production-Ready Medical AI System for Pneumonia Detection**

[![Hugging Face Space](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-yellow)](BURAYA_HUGGINGFACE_LINKINI_YAPISTIR)
[![Docker](https://img.shields.io/badge/Docker-Enabled-blue)](https://www.docker.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## 📌 Project Overview
PneumoVision AI is a specialized deep learning application designed to assist in the identification of **Pneumonia** from digital chest X-ray scans. The core engine is built on the **DenseNet121** architecture, fine-tuned for high-sensitivity medical imaging tasks.

To ensure seamless deployment and environment consistency, the entire application is containerized using **Docker** and hosted on Hugging Face Spaces.



---

## 🚀 Live Demo
Experience the AI in action directly in your browser:
👉 **[Click Here to Launch PneumoVision AI](https://huggingface.co/spaces/Ironside35/PneumoVision-AI)**

---

## 🛠️ Technical Implementation

### 1. Deep Learning Model
- **Architecture:** DenseNet121 (Transfer Learning from ImageNet).
- **Optimizer:** Adam with customized learning rate scheduling.
- **Preprocessing:** Grayscale to RGB conversion, 224x224 resizing, and Min-Max normalization.

### 2. Deployment Stack (The "B" Plan)
- **Frontend:** Streamlit for a clean, medical-grade UI.
- **Backend:** TensorFlow-CPU for efficient inference on cloud servers.
- **Containerization:** Custom Dockerfile to manage dependencies and system-level libraries.



---

## 📂 Repository Structure
```text
├── app.py                # Streamlit UI & Inference Logic
├── Dockerfile            # Container Configuration
├── requirements.txt      # Python Dependencies
├── rsna_heavyweight_model.h5  # Pre-trained CNN Model (35MB)
└── README.md             # Project Documentation
