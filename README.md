## 💳 Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fraudulent credit card transactions using Machine Learning classification algorithms. The project demonstrates an end-to-end ML workflow including data preprocessing, exploratory data analysis, feature scaling, model training, evaluation, and model comparison.

# 🎯 Project Objective

The main objective is to build machine learning models that can classify credit card transactions as:

0 → Legitimate Transaction
1 → Fraudulent Transaction

Since fraud detection is an imbalanced classification problem, the project evaluates models using multiple performance metrics rather than relying only on accuracy.

# 🤖 Machine Learning Models

The following classification algorithms were implemented and compared:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier

# 🛠️ Technologies Used
🐍 Python
🐼 Pandas
🔢 NumPy
📊 Matplotlib
📈 Seaborn
🤖 Scikit-learn
📓 Jupyter Notebook

# 🔍 Project Workflow
Dataset
   ↓
Data Exploration
   ↓
Data Cleaning
   ↓
Missing Value & Duplicate Check
   ↓
Class Distribution Analysis
   ↓
Feature Scaling
   ↓
Train-Test Split
   ↓
Model Training
   ├── Logistic Regression
   ├── Decision Tree
   └── Random Forest
   ↓
Model Evaluation
   ↓
Model Comparison

# 📊 Exploratory Data Analysis

The project includes visualizations for:

Fraud vs. legitimate transaction distribution
Transaction amount distribution
Feature correlation
Confusion matrix
Model performance comparison

# 📈 Model Evaluation

The models are evaluated using:

Metric	Purpose
Accuracy	Overall correct predictions
Precision	How many predicted fraud transactions were actually fraud
Recall	How many actual fraud transactions were detected
F1-Score	Balance between precision and recall
Confusion Matrix	Detailed classification performance
ROC-AUC	Ability to distinguish between fraud and legitimate transactions

⚠️ Why accuracy isn't enough

Credit card fraud datasets are typically imbalanced, meaning legitimate transactions greatly outnumber fraudulent transactions.

Therefore, a model can achieve high accuracy while still failing to detect fraudulent transactions.

For this reason, Precision, Recall, F1-Score, and the Confusion Matrix are important metrics in this project.

# 📂 Project Structure
Credit-Card-Fraud-Detection/
│
├── Dataset/
│   └── credit_card_fraud_detection.csv
│
├── Python/
│   └── Credit_Card_Fraud_Detection.ipynb
│
├── Screenshots/
│   ├── class_distribution.png
│   ├── confusion_matrix.png
│   └── model_comparison.png
│
└── README.md

# 💼 Business Use Case

Fraud detection models can help financial institutions:

Identify suspicious transactions
Reduce financial losses
Detect potentially fraudulent activity
Improve transaction monitoring
Support automated fraud screening

# 🚀 Key Skills Demonstrated

Data Cleaning | Exploratory Data Analysis | Feature Scaling | Classification | Logistic Regression | Decision Tree | Random Forest | Model Evaluation | Imbalanced Classification | Data Visualization | Python | Pandas | NumPy | Scikit-learn
