A financial analysis of a synthetic database from Kaggle.

Source: https://www.kaggle.com/datasets/umitka/synthetic-financial-fraud-dataset?resource=download

## About Dataset

This dataset contains 10,000 synthetic financial transactions designed for fraud detection research and model development. It simulates realistic user behavior and fraudulent patterns to provide a safe environment for testing machine learning models without exposing any real sensitive data.

### Key features include:

transaction_id: Unique identifier for each transaction

user_id: Identifier for the user performing the transaction

amount: Transaction amount (in local currency)

transaction_type: Type of transaction (POS, Online, ATM, QR)

merchant_category: Category of the merchant

country: Country where the transaction took place

hour: Hour of the transaction (0–23)

device_risk_score and ip_risk_score: Risk indicators for the device and IP

is_fraud: Label indicating if the transaction is fraudulent (1) or legitimate (0)

### Fraud patterns simulated include:

* Transactions with unusually high amounts
* Transactions in unusual countries for the user
* Night-time transactions
* Rapid multiple transactions
* Transactions from newly created accounts
* High-risk devices or IP addresses

### This dataset is ideal for:

* Training and testing fraud detection models
* Exploratory data analysis (EDA) of transaction behaviors
* Benchmarking anomaly detection algorithms
