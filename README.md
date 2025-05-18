Stock Forecasting with Hybrid Deep Learning and Anomaly Detection
This project leverages a hybrid approach combining deep learning, anomaly detection, and gradient boosting to forecast stock prices with improved accuracy and robustness.

Anomaly Detection for Data Cleaning
Isolation Forest: Removed extreme fluctuations and outliers from stock prices.

Autoencoder-Based Anomaly Detection: Identified irregularities in time-series patterns to ensure consistent data quality.

Impact: Reduced noise and improved the generalization ability of the forecasting model.

Autoencoder for Feature Extraction
Performed dimensionality reduction to eliminate redundant and noisy features.

Extracted meaningful representations that focus on core stock price movement patterns.

⏱Attention-Based LSTM for Temporal Learning
Incorporated an attention mechanism to focus on the most relevant time steps.

Enabled better capture of long-term dependencies and enhanced trend prediction.

XGBoost for Final Prediction
Combined features extracted from the Autoencoder and Attention-LSTM.

Employed XGBoost, a decision-tree-based ensemble model, for accurate final stock price forecasting.


