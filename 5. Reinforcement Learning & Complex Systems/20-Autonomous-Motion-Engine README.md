# 🏎️ NeuroDrive AI: Autonomous Motion Engine (Project 20/20)

<p align="center">
  <img src="https://img.shields.io/badge/Roadmap-20%2F20_Completed-gold?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Architecture-Neural_Motion_Planner-00ffcc?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Deployment-MLOps%20%7C%20Hugging%20Face-FF4B4B?style=for-the-badge" />
</p>

## 🎯 The Grand Finale: Spatial Intelligence
This project represents the 20th and final milestone of my comprehensive Data Science & AI roadmap. **NeuroDrive AI** is a high-precision trajectory prediction engine designed for autonomous urban environments. By analyzing high-frequency kinematic data from the **Lyft Level 5 Dataset**, the model predicts future movements of agents with centimeter-level accuracy.

---

## 🚀 Live Demo
The project is officially deployed and accessible as a real-time inference service:

👉 **[NeuroDrive Live Space on Hugging Face](https://huggingface.co/spaces/Ironside35/NeuroDrive-AI-Engine)**

---

## 🧠 Technical Deep Dive

### 📊 Performance Metrics
The model was evaluated using strict spatial error metrics to ensure safety-critical performance:
* **$R^2$ Score:** $0.9950$ (Captured 99.5% of spatial variance)
* **RMSE:** $0.0461$ meters (Average prediction error within cm-range)

### 🛠️ Tech Stack & MLOps
* **Modeling:** Random Forest Regressor & Neural MLP Architecture.
* **Feature Engineering:** 307-dimensional spatial vectorization including directional intensity and net displacement.
* **Pipeline:** Automated scaling with **StandardScaler** and model serialization via **Joblib**.
* **Serving:** Interactive UI built with **Streamlit**, hosted on **Hugging Face Spaces**.

