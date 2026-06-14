Credit Card Fraud Detection using Unsupervised Machine Learning
Project Overview

This project focuses on detecting fraudulent credit card transactions using Unsupervised Machine Learning techniques. Since fraud cases are extremely rare compared to normal transactions, traditional classification approaches may struggle with class imbalance.

To address this challenge, K-Means Clustering and Isolation Forest were implemented to identify anomalous transactions and compare their performance.

Objectives
Detect fraudulent credit card transactions.
Perform Exploratory Data Analysis (EDA).
Handle highly imbalanced transaction data.
Apply unsupervised anomaly detection techniques.
Compare K-Means and Isolation Forest performance.
Generate actionable fraud detection insights.
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Jupyter Notebook
Dataset Information

The dataset contains credit card transaction records with:

Time
Amount
PCA-transformed features (V1–V28)
Class Label
0 = Normal Transaction
1 = Fraud Transaction
Project Workflow
1. Data Loading & Exploration
Dataset inspection
Missing value analysis
Class distribution analysis
2. Exploratory Data Analysis (EDA)
Fraud vs Normal Transaction Analysis
Transaction Amount Distribution
Correlation Heatmap
3. Data Preprocessing
Feature Scaling using StandardScaler
Data Transformation
Feature & Target Separation
4. Dimensionality Reduction

Applied Principal Component Analysis (PCA) to reduce dimensionality and visualize transaction clusters.

5. K-Means Clustering
Created 2 clusters
Identified anomaly cluster
Classified suspicious transactions
6. Isolation Forest
Applied anomaly detection algorithm
Detected unusual transaction patterns
Converted anomaly predictions into fraud labels
7. Model Evaluation

Evaluated models using:

Confusion Matrix
Precision
Recall
Classification Report
Key Findings
Fraud Detection Challenge

Fraudulent transactions represent only a very small portion of total transactions, creating a highly imbalanced dataset.

K-Means Clustering
Groups similar transactions together.
Can identify anomaly clusters.
Limited effectiveness for rare fraud cases.
Isolation Forest
Specifically designed for anomaly detection.
Better suited for identifying unusual transactions.
Performs more effectively on highly imbalanced datasets.
PCA Visualization

PCA helped visualize transaction clusters and understand anomaly separation.

Business Impact
Early fraud detection can reduce financial losses.
Unsupervised learning enables fraud monitoring even without labeled data.
Isolation Forest provides an effective approach for anomaly-based fraud detection systems.
Skills Demonstrated
Exploratory Data Analysis (EDA)
Data Preprocessing
Feature Scaling
PCA (Principal Component Analysis)
K-Means Clustering
Isolation Forest
Anomaly Detection
Machine Learning
Model Evaluation
Fraud Analytics
Installation

Clone the repository:

git clone https://github.com/yourusername/credit-card-fraud-detection.git

Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn

Run Jupyter Notebook:

jupyter notebook

Open:

ML_Fraud_Project_Ritik-Kosta.ipynb

Future Enhancements
Supervised Fraud Detection Models
Random Forest & XGBoost Comparison
Hyperparameter Optimization
Real-Time Fraud Detection System
Interactive Dashboard using Power BI or Streamlit
Learning Outcomes

Through this project, I gained practical experience in:

Unsupervised Machine Learning
Fraud Detection Techniques
Anomaly Detection
PCA Visualization
Model Evaluation
Business-Oriented Data Analytics
Author

Ritik Kosta

Aspiring Data Analyst | Python | SQL | Power BI | Machine Learning

License

This project is developed for educational and portfolio purposes.
