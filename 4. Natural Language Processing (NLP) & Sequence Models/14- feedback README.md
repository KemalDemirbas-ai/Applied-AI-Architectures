# 🛡️ Neural Discourse Evaluator: Advanced Student Writing Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
</p>

## 🚀 Overview
The **Neural Discourse Evaluator** is an industrial-grade NLP engine designed to autonomously identify and classify structural elements in long-form student essays. Utilizing a **Deep Bidirectional LSTM (Bi-LSTM)** architecture, the system understands sequential context to categorize text into classes like *Claims, Evidence, Counterclaims,* and *Concluding Statements.*

This project represents the 14th deployment in our 20-project **Advanced AI Portfolio**, demonstrating a complete transition from research (Kaggle) to production (Hugging Face).

---

## 📊 Industrial Performance
- **Peak Validation Accuracy:** 77.7%+ (Stable across 7 discourse classes)
- **Architecture:** Bi-LSTM with SpatialDropout1D and CuDNN Optimization.
- **Inference Pipeline:** Integrated Tokenizer with post-padding sequence alignment.

---

## 🛠️ The 10-Step MLOps Compliance Framework
This project follows a strict, scalable engineering pipeline:
1.  **Objective:** Multi-class sequence classification of student writing.
2.  **EDA:** Deep analysis of class distributions and sequence lengths.
3.  **Feature Selection:** Isolation of discourse text and structural targets.
4.  **Categorical Mapping:** Numeric encoding of 7 distinct discourse types.
5.  **Data Cleansing:** Regex-driven noise reduction and semantic standardization.
6.  **Feature Engineering:** Extraction of NLP meta-metrics (word counts, char density).
7.  **Vectorization:** Neural-ready integer mapping via Keras Tokenizer.
8.  **Data Splitting:** 15% strict validation isolation to prevent data leakage.
9.  **Model Training:** Bi-LSTM deployment with EarlyStopping and dynamic Learning Rates.
10. **Evaluation:** Interactive performance visualization using Plotly Neon charts.

---

## 🌐 Live System Deployment
The neural brain (`.keras`) and its corresponding dictionary (`tokenizer.pkl`) are currently serving real-time inference on Hugging Face Spaces.

👉 **[Launch Live Demo on Hugging Face](https://huggingface.co/spaces/Ironside35/neural-discourse-evaluator)**

