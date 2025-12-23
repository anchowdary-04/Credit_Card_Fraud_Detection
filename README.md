# Credit_Card_Fraud_Detection
This project detects fraudulent credit card transactions using machine learning techniques on a real-world dataset. The goal is to identify whether a transaction is **fraudulent** or **legitimate** based on historical transaction patterns and features.

## Dataset
The dataset used in this project is larger than GitHub's file size limit and is therefore not included in this repository.
You can download a publicly available version of the dataset here:  
[Kaggle: Credit Card Fraud Detection Dataset](https://www.kaggle.com/code/gpreda/credit-card-fraud-detection-predictive-models/input?select=creditcard.csv)

After downloading, place the CSV file inside the following directory:
data/creditcard.csv

### Dataset Description
The dataset contains anonymized credit card transaction records. It includes hundreds of thousands of transactions, but only a very small percentage of them are fraudulent, making this a classic **imbalanced classification problem** commonly addressed in financial fraud detection.

---
##  Project Overview
Credit card fraud is a critical problem in the financial industry, where attackers exploit payment systems to make unauthorized transactions. The project applies data preprocessing, exploratory data analysis (EDA), and supervised machine learning algorithms to build a detection model that can flag suspicious transactions with high precision and recall. :contentReference[oaicite:1]{index=1}

###  Key Steps
- Load and understand the dataset  
- Handle class imbalance (fraud cases are very rare)  
- Train one or more classification models  
- Evaluate performance using metrics like confusion matrix, precision, recall, and ROC curves  
- Save and interpret the model for future use

---

## Tech Stack

| Component | Tools / Libraries |
|-----------|------------------|
| Language | Python |
| Data Manipulation | pandas, numpy |
| Visualization | matplotlib, seaborn |
| Machine Learning | scikit-learn, imbalanced-learn (if used) |
| Notebook | Jupyter Notebook |

---



