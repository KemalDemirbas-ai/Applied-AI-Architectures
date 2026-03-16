# 🤖 : Autonomous Decision Matrix 
> **Industrial Reinforcement Learning & Functional Policy Engine**

[![Hugging Face Space](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue)](https://huggingface.co/spaces/Ironside35/autonomous-decision-matrix)
[![Python-Version](https://img.shields.io/badge/Python-3.9+-green.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://tensorflow.org/)
[![License-MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🎯 Vision & Scope
This project is the 16th structural component of the **"Nova"** autonomous ecosystem. It transcends classical regression and classification models to demonstrate how an autonomous agent can execute strategic decisions in a dynamic environment (Connect X). At the heart of the project is an **Imitation Learning** algorithm designed to replicate expert strategies.

## 🚀 Live Deployment (Hugging Face)
The trained autonomous brain (`connect_brain.h5`) is currently serving as a live game engine on Hugging Face Spaces.

👉 **[Nova: Autonomous Decision Matrix Live Demo](https://huggingface.co/spaces/Ironside35/autonomous-decision-matrix)**

---

## 🧠 Technical Architecture: "For-Free" Paradigm
The defining characteristic of this project is the use of **Functional Programming** and **Vectorized Operations**. The system strictly avoids traditional `for` loops:
- **Zero-Loop Logic:** Utilizes NumPy vectorization and Python's `map`/`next` functions to optimize decision speed.
- **Neural Engine:** A Deep Multilayer Perceptron (MLP) that performs real-time analysis of the 42-cell game board.
- **Inference Speed:** Real-time response with a latency of less than 10ms per move.

---

## ⚙️ 10-Step Industrial MLOps Discipline
The pipeline was engineered according to the industrial standards of the "Artificial Intelligence and Data Science Training Camp" instructed by Zafer Acar:

1.  **Objective Definition:** Defined autonomous move prediction and strategic prioritization.
2.  **Data Simulation:** Synthetic generation of 10,000+ expert-level board states.
3.  **Feature Selection:** Isolation of 42 game cells (board state) as primary inputs.
4.  **Numeric Transformation:** Mapping player tokens into neural-ready numeric formats.
5.  **Data Cleansing:** Implementation of strict filters for illegal moves and column capacity.
6.  **Feature Engineering:** Calculation of "Center Dominance" and "Game Phase" metrics.
7.  **Vectorization:** One-Hot encoding of the 7-column action space.
8.  **Data Splitting:** Maintaining a 20% validation set to ensure strategy generalization.
9.  **Model Training:** Activation of a Deep Policy Network using Keras.
10. **Productization:** Deployment of a live, interactive Streamlit-based game engine.

