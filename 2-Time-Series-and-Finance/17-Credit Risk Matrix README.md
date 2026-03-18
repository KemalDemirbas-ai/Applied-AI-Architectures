# 🛡️ Nova: Credit Risk Matrix
> **Project #17 of 20 | Industrial Financial Engineering & Deep Learning Pipeline**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Hugging%20Face-blue?style=for-the-badge&logo=huggingface)](https://huggingface.co/spaces/Ironside35/credit-risk-matrix)
[![Framework](https://img.shields.io/badge/TensorFlow-Keras-orange?style=for-the-badge&logo=tensorflow)]()
[![UI](https://img.shields.io/badge/Streamlit-App-red?style=for-the-badge&logo=streamlit)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🎯 Vision & Scope
This repository houses the 17th architectural milestone of the **Nova Ecosystem**. Tackling one of the most critical challenges in quantitative finance—Credit Default Prediction—this engine calculates the probability of a customer defaulting on their credit balance using the massive American Express dataset.

This predictive safeguard module is designed to operate autonomously, laying the foundational risk-management architecture for future corporate operations in Estonia.

## 🚀 Live Neural Brain
The trained Keras deep learning model (`amex_brain.h5`) is deployed and interacting with data in real-time via a custom Streamlit web interface. 

👉 **[TEST THE LIVE AI ENGINE HERE](https://huggingface.co/spaces/Ironside35/credit-risk-matrix)**

## 🧠 Technical Architecture & RAM Mastery
Working with massive tabular financial data requires industrial-grade memory management. This pipeline was built to survive extreme computing constraints:
- **Surgical Extraction:** Bypassed standard OOM (Out-of-Memory) kernel crashes by utilizing strict `usecols` loading and dynamic garbage collection (`gc.collect()`).
- **For-Free Paradigm:** 100% vectorized Pandas operations for missing value median imputation and feature engineering. Zero `for` loops used.
- **Deep Neural Engine:** A TensorFlow/Keras Multi-Layer Perceptron (MLP) heavily optimized to catch highly imbalanced default events.

## ⚙️ Industrial MLOps Pipeline
Developed under the strict, high-performance standards of the *Mastering Applied Data Science with Deep Learning* program:
1. **Data Ingestion:** Memory-optimized extraction of targeted financial indicators (P_2, B_1, D_39, R_1, S_2).
2. **Feature Engineering:** Vectorized generation of custom risk metrics (e.g., `risk_ratio`).
3. **Brain Training:** Keras Deep Learning with Dropout and Batch Normalization layers.
4. **Productization:** End-to-end deployment to Hugging Face Spaces for autonomous web inference.

---
**Architect:** AI Mimar  
**Status:** Project 17/20 COMPLETE ✅
