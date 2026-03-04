🛡️ AI Financial Anomaly Engine: Autonomous Security Pipeline
This repository features a high-performance Cyber-Security & FinTech pipeline developed for the IEEE-CIS Fraud Detection challenge.
The project transforms over 500,000 rows of complex, anonymized financial data into a real-time predictive security layer using an optimized Gradient Boosting approach.

🚀 Performance Snapshot
Final Validation Score: 0.9303 ROC-AUC

Architecture: Optimized XGBoost Classifier

Inference Latency: ~0.12 ms (Engineered for high-frequency trading environments)

Status: Deployment Ready (Hugging Face Spaces)

🛠️ The 10-Step Engineering Pipeline
The project follows a rigorous machine learning lifecycle to ensure model convergence and zero data leakage:

1️⃣ Project Definition & Metric Selection

Objective: Detect fraudulent transactions in real-time within highly imbalanced global datasets.

KPI: Evaluated via ROC-AUC to ensure high precision-recall balance even in cases where fraud is less than 3% of the data.

2️⃣ Exploratory Data Analysis (EDA)

Data Health Check: Audited 590,000+ entries for structural integrity and missing value patterns.

Anomaly Mapping: Visualized the correlation between transaction amounts, time-deltas, and fraud probability.

3️⃣ Feature Engineering & Optimization

Identity Clustering: Engineered features from C1-C14 identity columns to capture user behavior patterns.

Temporal Decomposition: Transformed raw time-deltas into cyclic features for day/hour pattern recognition.

Target Encoding: Optimized categorical variables to handle high-cardinality features without dimensionality explosion.

4️⃣ Memory & Performance Management

RAM Optimization: Downcasted numerical features to float32 to reduce memory footprint by 60%.

Standard Scaling: Applied rigorous scaling to ensure stable gradient flow during the boosting process.

🧠 Machine Learning Architecture: XGBoost Engine
The model utilizes a custom-tuned XGBoost architecture for maximum non-linear pattern recognition:

Boosting Rounds: Optimized via early stopping to prevent overfitting.

Class Balancing: Implemented scale_pos_weight to handle extreme fraud-to-genuine imbalance.

Regularization: L1 (Lasso) and L2 (Ridge) penalties applied to maintain model generalization.
Phase,ROC-AUC Score,Status
Baseline,0.8122,Initial Training
Hyperparameter Tuning,0.8944,Feature Optimization
Final Production Model,0.9303,Deployment Ready
