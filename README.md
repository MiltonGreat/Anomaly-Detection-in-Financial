# Anomaly Detection in Financial Transactions

This repository shows projects dealing with anomaly detection in finance for fraud detection, risk assessment, and trading anomalies. Here are datasets where I applied anomaly detection techniques to simulate realistic financial scenarios and refine my data science skills.

### 1. Credit Card Fraud Detection (Financial Fraud)

**Dataset:** Credit Card Fraud Detection

**Description:** This dataset contains 284,807 credit card transactions, labeled as fraudulent (1) or non-fraudulent (0). Due to the highly imbalanced nature (~0.17% fraud cases), it is excellent for anomaly detection.

**What I Did in the Project:**

- **Fraud Detection:** Used autoencoders, isolation forests, and one-class SVM to detect fraudulent transactions.
- **[Time-Based Anomaly Analysis:](https://github.com/MiltonGreat/Time-Based-Anomaly-Analysis.git)** Identified sudden spending spikes within short time frames.
- **Feature Engineering:** Applied PCA and t-SNE to visualize fraud patterns and improve classification accuracy.

### 2. Synthetic Bank Transactions (Money Laundering & Unusual Spending Patterns)

**Dataset:** Synthetic Bank Transactions (PaySim)

**Description:** This dataset consists of simulated financial transactions that mimic real-world banking fraud, including transaction types (CASH_OUT, TRANSFER, PAYMENT), timestamps, and fraud labels.

**What I Did in the Project:**

- **[Transaction Risk Analysis:](https://github.com/MiltonGreat/Transaction-Risk-Analysis.git)** Implemented Local Outlier Factor (LOF) to score transactions for fraud risk.

### 3. Forex Exchange Rates & Trading (Market Manipulation & Flash Crashes)

**Dataset:** Forex Exchange Rates

**Description:** This dataset contains daily exchange rates from 2000 to 2019 for major currencies. It is useful for detecting market anomalies and currency risk analysis.

**What I Did in the Project:**

- **Detect Flash Crashes:** Used rolling z-scores to identify sudden exchange rate drops.
- **Currency Manipulation Analysis:** Applied time-series anomaly detection techniques to find suspicious trading patterns.
- **High-Volatility Periods:** Built LSTM-based models to predict major fluctuations in the forex market.
