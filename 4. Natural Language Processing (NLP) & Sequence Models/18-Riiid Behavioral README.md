# 🎓 Project #18: Riiid Behavioral Education AI
> **Sequential Knowledge Tracing & Adaptive Learning Intelligence**

<p align="center">
  <img src="https://img.shields.io/badge/Status-Project%2018%20of%2020-00ffcc?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ROC--AUC-0.7677-ff007f?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Architecture-LightGBM-00bfff?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" />
</p>

## 🚀 Live Demo (Hugging Face)
The model is deployed and currently performing autonomous inferences. You can test the system via the link below:

👉 **[RIIID BEHAVIORAL AI - LIVE DEMO](https://huggingface.co/spaces/Ironside35/riiid-behavioral-ai)**

---

## 🎯 Project Vision
This study marks the 18th milestone of my 20-project industrial roadmap. It addresses the **"Knowledge Tracing"** challenge, a cornerstone of EdTech. Using the massive Riiid dataset (over 100 million student-question interactions), I developed an autonomous engine capable of predicting whether a student will correctly answer their next question with a precision of **0.7677 ROC-AUC**.

---

## ⚙️ 10-Step Industrial MLOps Protocol
The project was constructed following a strict "Senior Architect" discipline across these 10 core rules:

1.  **Objective:** Defining educational success (Correct/Incorrect) as a binary classification task.
2.  **Deep Inspection:** Mapping the data's DNA (EDA) using `info()`, `describe()`, and `isnull()`.
3.  **Selection:** Isolating high-signal features through strategic selection.
4.  **RAM Optimization:** Optimizing data types to `int8` and `float32` (Saving 75% in memory usage).
5.  **Data Manipulation:** Vectorized handling of time-series gaps and null values.
6.  **Feature Engineering:** Generating dynamic metrics for **User Accuracy Rate** and **Content Difficulty**.
7.  **Encoding:** Transforming behavioral signals into high-performance numerical tensors.
8.  **Temporal Splitting:** Segmenting data into Training and Test sets while maintaining chronological integrity.
9.  **Model Fitting:** Training a **LightGBM** engine capable of processing massive datasets in seconds.
10. **Evaluation:** Validating performance using **ROC-AUC** and **Confusion Matrix** industrial standards.

---

## 📊 Performance Summary
The model yielded the following results on a holdout set of over 200,000 interactions:

| Metric | Score | Significance |
| :--- | :--- | :--- |
| **ROC-AUC** | **0.7677** | **Master Tier.** Exceptional probability calibration. |
| **Accuracy** | **72.59%** | Strong predictive power across complex behavioral logs. |
| **Memory Mgmt** | **Critical Success** | Processed 100M+ rows without exceeding RAM limits. |

---

## 🛠️ Tech Stack
* **Engine:** LightGBM (Gradient Boosting)
* **Interface:** Streamlit (Hugging Face Spaces)
* **Processing:** Pandas, NumPy (Vectorized Logic)
* **Packaging:** Joblib

---

## ⚖️ License (MIT License)
This project is licensed under the MIT License.
**Copyright (c) 2026 Kemal Demirbaş**

---

**Architect:** Kemal Demirbaş  
**Status:** **Project 18/20 COMPLETE ✅**
