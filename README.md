# Anomaly Detection in Financial Transactions

This repository shows projects dealing with anomaly detection in finance for fraud detection, risk assessment, and trading anomalies. Here are datasets where I applied anomaly detection techniques to simulate realistic financial scenarios and refine my data science skills.

### 1. Credit Card Fraud Detection (Financial Fraud)

**Dataset:** Credit Card Fraud Detection

**Description:** This dataset contains 284,807 credit card transactions, labeled as fraudulent (1) or non-fraudulent (0). Due to the highly imbalanced nature (~0.17% fraud cases), it is excellent for anomaly detection.

**What I Did in the Project:**

- **Fraud Detection:** Used autoencoders, isolation forests, and one-class SVM to detect fraudulent transactions.
- **Time-Based Anomaly Analysis:** Identified sudden spending spikes within short time frames.
- **Feature Engineering:** Applied PCA and t-SNE to visualize fraud patterns and improve classification accuracy.

### 2. Synthetic Bank Transactions (Money Laundering & Unusual Spending Patterns)

**Dataset:** Synthetic Bank Transactions (PaySim)

**Description:** This dataset consists of simulated financial transactions that mimic real-world banking fraud, including transaction types (CASH_OUT, TRANSFER, PAYMENT), timestamps, and fraud labels.

**What I Did in the Project:**

- **Money Laundering Detection:** Identified high-volume cash movements occurring in short periods.
- **Unusual Spending Behavior:** Used DBSCAN clustering to detect customers with outlier spending patterns.
- **Transaction Risk Analysis:** Implemented Local Outlier Factor (LOF) to score transactions for fraud risk.

### 3. Loan Default Prediction (Credit Risk Anomalies)

**Dataset:** Home Credit Default Risk

**Description:** This dataset includes loan applications, customer financial history, and default risk. It is valuable for credit risk modeling and anomaly detection.

**What I Did in the Project:**

- **Detect High-Risk Borrowers:** Applied k-means clustering to identify borrowers with unusual repayment behavior.
- **Anomaly Detection in Credit Histories:** Used autoencoders to find borrowers with inconsistent income patterns.
- **Early Warning System:** Developed a system to predict defaults before they happen, helping lenders mitigate risk.

### 4. Forex Exchange Rates & Trading (Market Manipulation & Flash Crashes)

**Dataset:** Forex Exchange Rates

**Description:** This dataset contains daily exchange rates from 2000 to 2019 for major currencies. It is useful for detecting market anomalies and currency risk analysis.

**What I Did in the Project:**

- **Detect Flash Crashes:** Used rolling z-scores to identify sudden exchange rate drops.
- **Currency Manipulation Analysis:** Applied time-series anomaly detection techniques to find suspicious trading patterns.
- **High-Volatility Periods:** Built LSTM-based models to predict major fluctuations in the forex market.

### 5. Stock Market Trading Data (Pump-and-Dump Schemes & Irregular Trading)

**Dataset:** S&P 500 Stock Prices

**Description:** This dataset contains daily stock prices for S&P 500 companies over 10 years, including Open, High, Low, Close (OHLC) prices, volume, and adjusted close prices.

**What I Did in the Project:**

- **Pump-and-Dump Detection:** Identified sharp price spikes followed by rapid drops.
- **Unusual Volume Spikes:** Detected sudden and unexplained volume surges using time-series anomaly models.
- **Insider Trading Signals:** Used market movement analysis to find abnormal price shifts before major news events.

### 6. Financial Sentiment & News Impact (Fake News & Market Manipulation)

**Dataset:** Stock Market Sentiment Dataset

**Description:** This dataset contains financial news headlines and their impact on stock markets, including tweets from influential figures (e.g., political and business leaders).

**What I Did in the Project:**

- **Detect Market Manipulation:** Used NLP-based anomaly detection to identify fake financial news.
- **Sentiment vs. Stock Price Anomalies:** Found cases where positive news correlated with unexpected price drops.
- **Event-Based Trading Irregularities:** Applied outlier detection techniques to flag unusual stock movements following major news events.

### 7. Banking Customer Transactions (Unusual Spending Behaviors)

**Dataset:** Bank Customer Transactions

**Description:** This dataset contains simulated bank transactions, including customer IDs, transaction amounts, and merchant categories. It is useful for detecting spending pattern anomalies and fraudulent activity.

**What I Did in the Project:**

- **Spending Behavior Outliers:** Identified customers with sudden high-value transactions.
- **Merchant Category Fraud:** Detected unexpected transactions in high-risk categories.
- **Transaction Velocity Anomalies:** Analyzed transaction frequency spikes to flag potential fraud cases.

### 8. Ethereum Blockchain Transactions (Cryptocurrency Fraud & Anomalies)

**Dataset:** Ethereum Blockchain Transactions

**Description:** This dataset contains Ethereum blockchain transaction records with timestamps, useful for crypto trading analysis and fraud detection.

**What I Did in the Project:**

- **Crypto Wallet Anomalies:** Used graph-based anomaly detection to identify wallets with unusual transaction frequencies.
- **Wash Trading & Fake Volume:** Applied clustering techniques to detect traders engaging in self-trading to manipulate markets.
- **Smart Contract Exploit Detection:** Used time-series anomaly detection to identify malicious smart contract activity.
