# 📈 Project 19: Optiver - High-Frequency Volatility Engine

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Quantitative_Finance-00ffcc?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Architecture-LightGBM-00bfff?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Deployment-Streamlit%20%7C%20Hugging%20Face-FF4B4B?style=for-the-badge" />
</p>

## 🎯 Executive Summary
Welcome to the **19th industrial-scale project** of my Data Science & MLOps portfolio. 

This repository contains the architecture and deployment pipeline for an autonomous AI engine that predicts the **Realized Volatility** of financial markets using microsecond-level High-Frequency Trading (HFT) Order Book data. 

Instead of treating this as a simple tabular regression problem, this project focuses on **Big Data Optimization** and **MLOps Deployment**. By utilizing pure Numpy vectorization, we bypass traditional memory leaks associated with massive `.parquet` files, transforming raw Bid/Ask spreads into actionable market intelligence.

---

## 🚀 Live Application (Deployed on Hugging Face)
A machine learning model is only as good as its deployment. The trained Neural Engine has been exported as a `.pkl` microservice and is currently live with a custom Streamlit UI.

👉 **[Launch the Live Autonomous Engine Here](https://huggingface.co/spaces/Ironside35/Optiver-Volatility-Engine)**

---

## ⚙️ Technical Architecture & Pipeline

### 1. Feature Engineering (The Quant Approach)
* **WAP (Weighted Average Price):** Calculated the true equilibrium price leveraging both Bid and Ask volumes.
* **Logarithmic Returns:** Transformed raw price fluctuations into mathematically stable log returns.
* **Realized Volatility:** Engineered the primary target variable directly from the temporal log returns to capture market clustering.

### 2. Surgical Memory Management
Processed gigabytes of partitioned `.parquet` files. Replaced standard Pandas `.apply(lambda)` loops with **Pure Vectorization** (`np.log().diff()`) to achieve lightning-fast data transformations without bottlenecking the 16GB RAM limit.

### 3. The Predictive Engine
* **Algorithm:** Highly optimized `LightGBM Regressor`.
* **Validation:** Evaluated using Root Mean Squared Error (RMSE), achieving high precision in tracking volatility spikes during market panic scenarios.

---

## 💻 How to Run Locally

If you wish to test the engine on your local machine:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/Optiver-Volatility-Engine.git](https://github.com/YOUR_GITHUB_USERNAME/Optiver-Volatility-Engine.git)
   cd Optiver-Volatility-Engine
