Project Overview

This project focuses on detecting fraudulent credit card transactions using unsupervised machine learning techniques. Fraud detection is a highly imbalanced classification problem where fraudulent transactions represent a very small percentage of total transactions.
The objective of this project is to identify anomalous transaction patterns using clustering and anomaly detection models and compare their performance.

Dataset Description

The dataset contains anonymized credit card transaction features.
The target variable:
is_fraud (or Class)
0 → Normal Transaction
1 → Fraudulent Transaction
The dataset is highly imbalanced, making anomaly detection techniques suitable.

Methodology :
1️) Data Preprocessing :

Checked missing values
Performed exploratory data analysis (EDA)
Generated correlation heatmap
Standardized features using StandardScaler
Separated features and target variable

2) Models Implemented

KMeans Clustering
DBSCAN
Isolation Forest

3️) Model Evaluation Metrics :

Due to class imbalance, the following metrics were used:

Precision
Recall
F1-score
Confusion Matrix
ROC-AUC

Technologies Used :

Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn

