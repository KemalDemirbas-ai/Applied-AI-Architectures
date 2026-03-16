# 🛡️ Neural Extraction Engine: Tweet Sentiment Sequence Tagging

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white" />
  <a href="https://huggingface.co/spaces/Ironside35/tweet-sentiment-extractor">
    <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  </a>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
</p>

## 🚀 Overview
Welcome to the **Neural Extraction Engine**, an industrial-grade NLP system designed for **Contextual Substring Extraction**. [cite_start]Unlike traditional classification models that simply label a text as 'positive' or 'negative', this engine utilizes **Sequence Tagging** to autonomously isolate and extract the exact phrase (substring) that dictates the sentiment of a tweet[cite: 14].

[cite_start]This project marks the 15th milestone in our Advanced Machine Learning portfolio, demonstrating a complete end-to-end MLOps pipeline from Kaggle data ingestion to Hugging Face cloud deployment[cite: 5, 14, 15].

---

## 🌐 Live System Deployment
The neural brain (`.keras`) and its optimized token dictionary are currently serving real-time inference on Hugging Face Spaces.

👉 **[Launch the Live Extraction Engine Here](https://huggingface.co/spaces/Ironside35/tweet-sentiment-extractor)**

---

## 🧠 Core Architecture
- **Framework:** TensorFlow / Keras
- **Model:** Deep Bidirectional LSTM (Bi-LSTM) with `TimeDistributed` Dense layers.
- **Task:** Token-level binary classification (Sequence Tagging) mapped to original string outputs.
- **Optimization:** `SpatialDropout1D` for robust anti-overfitting and custom `<OOV>` dynamic filtering for clean substring reconstruction.

---

## 🛠️ The 10-Step MLOps Compliance Framework
[cite_start]This system was engineered following a strict, scalable pipeline[cite: 89, 90, 91, 92, 93, 94, 95, 96, 97, 98]:
1.  **Objective:** Token-level extraction of sentiment spans.
2.  **EDA:** Distribution analysis of sentiments and word counts.
3.  **Feature Selection:** Isolation of source text and target substrings.
4.  **Categorical Mapping:** Numeric encoding of sentiment context.
5.  **Data Cleansing:** Regex-driven noise reduction and dynamic whitespace trimming.
6.  **Feature Engineering:** Calculation of extraction ratios and spatial metrics.
7.  **Vectorization:** Binary target masking and token padding sequence alignment.
8.  **Data Splitting:** 15% strict validation isolation to prevent data leakage.
9.  **Model Training:** Time-distributed Bi-LSTM deployed with EarlyStopping.
10. **Deployment:** Streamlit-based Web UI integrated with Hugging Face ecosystem.

