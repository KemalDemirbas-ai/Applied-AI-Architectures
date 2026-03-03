🛒 Retail Intelligence: Store Sales Forecasting Engine

This repository features a high-performance Time Series Forecasting pipeline developed for the Corporación Favorita grocery sales competition.

The project transforms over 3 million rows of raw retail data into predictive market intelligence using a deep sequence learning approach.

🚀 Performance Snapshot

Final Training Score: 0.36 RMSLE

Architecture: Deep LSTM (Long Short-Term Memory)

Status: Deployment Ready (Hugging Face Spaces)

🛠️ The 10-Step Engineering Pipeline

The project follows a rigorous machine learning lifecycle to ensure data integrity and model convergence:

1️⃣ Project Definition & Metric Selection

Objective:
Predict unit sales for thousands of items across 54 stores.

KPI:
Evaluated via RMSLE:

√(1/n Σ (log(pi + 1) - log(ai + 1))²)

RMSLE penalizes under-predictions and over-predictions equally on a logarithmic scale.

2️⃣ Exploratory Data Analysis (EDA)

Macro Trend Blueprint: Visualized the 2013–2017 sales trajectory using Plotly & Seaborn.

Data Health Check: Audited 3,000,888 entries for null values and structural integrity.

3️⃣ Feature Engineering & Optimization

The Logarithmic Hack: Applied np.log1p() to stabilize variance → score improved from ~3.15 to 0.36

Temporal Decomposition: Extracted Year, Month, Day, Day of Week

Categorical Encoding: One-Hot Encoding for Store Number & Product Family

4️⃣ Memory & Performance Management

RAM Optimization: Downcasted features to float32

Standard Scaling: Applied StandardScaler for stable gradient flow

🧠 Deep Learning Architecture

The model utilizes a stacked LSTM engine for sequence dependency modeling:

Layer 1: LSTM (64 units, ReLU, return_sequences=True)

Layer 2: LSTM (32 units, ReLU)

Regularization: Dropout (0.2)

Dense Head: 32-unit fully connected layer

Output: Single regression neuron

📈 Training Results & Analytics

Training configuration:

batch_size = 2048

epochs = 5

Epoch	Training Loss (MSE)	Validation Loss (MSE)
1	3.1261	1.0146
2	0.3749	1.3622
