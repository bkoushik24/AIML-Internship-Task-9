# AIML-Internship-Task-9
Machine Learning project for detecting fraudulent credit card transactions using Random Forest and Logistic Regression, handling class imbalance with oversampling, and evaluating performance using precision, recall, and F1-score.

💳 Credit Card Fraud Detection – Random Forest
📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning. Fraud detection is a highly imbalanced classification problem where fraudulent cases are very rare compared to legitimate transactions.

The project builds and compares:
1.Logistic Regression (Baseline Model)
2.Random Forest Classifier (Ensemble Model)

Special care is taken to handle class imbalance and evaluate the model using proper metrics such as precision, recall, and F1-score.

📊 Dataset Information

The dataset contains simulated credit card transactions with the following features:

1.amount – Transaction amount
2.time – Transaction time
3.v1, v2, v3 – Transformed transaction features
4.Class – Target variable
5.0 → Non-Fraud
6.1 → Fraud
⚠ The dataset is highly imbalanced (fraud cases are very few).

⚙️ Tools & Technologies Used

1.Python
2.Pandas
3.NumPy
4.Scikit-learn
5.Matplotlib
6.Joblib

🔄 Project Workflow
1️⃣ Data Loading & Exploration

1.Checked class distribution
2.Identified imbalance issue

2️⃣ Data Preprocessing

1.Separated features and target
2.Stratified train-test split
3.Manual oversampling of minority class

3️⃣ Feature Scaling

1.Applied StandardScaler (for Logistic Regression)

4️⃣ Model Training

1.Trained Logistic Regression (baseline)
2.Trained Random Forest (n_estimators=100)

5️⃣ Model Evaluation

Evaluated using:

1.Precision
2.Recall
3.F1-score
4.Confusion Matrix

6️⃣ Feature Importance

1.Identified most important fraud indicators

7️⃣ Model Saving

1.Saved final Random Forest model using Joblib

