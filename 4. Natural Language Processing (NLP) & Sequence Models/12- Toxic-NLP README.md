
<div align="center">
  <h1>🛡️ AI Moderation Engine</h1>
  <h3>Autonomous Multi-Label NLP Pipeline</h3>
  
  [![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
  [![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0+-FF6F00.svg)](https://tensorflow.org)
  [![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B.svg)](https://streamlit.io/)
</div>

---

## 🚀 The Vision: Engineering a Moderation Factory
This project goes beyond training a simple machine learning model; it establishes a **fully automated MLOps pipeline** for Natural Language Processing. Built to analyze and classify digital text streams in real-time, this engine detects 6 distinct dimensions of toxicity simultaneously without data leakage.

## 🧠 Neural Architecture
The core intelligence is powered by a **Bidirectional LSTM (Bi-LSTM)** network. Unlike traditional models that read text in one direction, this engine reads sentences from both ends. This allows the AI to grasp deep semantic context and avoid triggering false alarms on metaphorical or sarcastic language.

* **Vectorization:** Zero-loop, GPU-accelerated `TextVectorization`.
* **Embeddings:** High-dimensional semantic mapping (`mask_zero` optimized).
* **Context Extraction:** Bi-LSTM paired with Global MaxPooling.
* **Multi-Label Output:** 6-node Dense layer with Sigmoid activation for independent probability scoring across all threat vectors.

---

## 📊 Performance Metrics
The neural engine was rigorously tested against unseen validation data, proving its industrial reliability in distinguishing between safe conversations and critical digital threats.
* **Validation ROC-AUC Score:** `> 0.975`

**Toxicity Dimensions Monitored:**
`Toxic` | `Severe Toxic` | `Obscene` | `Threat` | `Insult` | `Identity Hate`

---

## 💻 Local Execution
The system is packaged in the modern, fail-safe `.keras` format to prevent legacy lookup table initialization errors during cloud deployment.

To run this AI factory on your local machine:
```bash
git clone [https://huggingface.co/spaces/Ironside35/AI-Moderation-Engine]

