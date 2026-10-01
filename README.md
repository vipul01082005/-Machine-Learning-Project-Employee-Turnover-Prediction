# Employee Turnover Prediction

A supervised machine learning project that predicts whether an employee is likely to leave an organization based on employee-related features.

## 📌 Project Overview

Employee turnover can have a significant impact on organizations. This project uses machine learning classification techniques to identify patterns associated with employee attrition and predict potential employee turnover.

The project follows an end-to-end machine learning workflow, starting from data preprocessing and exploratory data analysis (EDA) to model training and evaluation.

## 🎯 Objective

The main objectives of this project are:

- Analyze employee data
- Perform data preprocessing and exploratory data analysis
- Identify important factors related to employee turnover
- Train supervised machine learning models
- Evaluate model performance using classification metrics
- Predict employee turnover

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Selection / Preprocessing
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Employee Turnover Prediction

📊 Dataset

The project uses an employee turnover dataset containing various employee-related attributes and a target variable representing employee turnover.

The test set used for evaluation contains 216 samples.

🤖 Models Evaluated

The following models were evaluated:

* Baseline Model
* Lasso
* Ridge


📈 Model Performance

The models were evaluated using accuracy and F1-score.
Model

Accuracy

Macro F1-Score

Baseline

87.96%

0.88

Lasso

89.81%

0.90

Ridge

87.96%

0.88

Lasso Classification Report

The Lasso model achieved an accuracy of 89.81% on the test set.

Class

Precision

Recall

F1-Score

0

0.87

0.95

0.90

1

0.94

0.85

0.89

Macro Average

0.90

0.90

0.90

🔍 Key Observations

* The baseline model achieved an accuracy of 87.96%.
* The Lasso model achieved an accuracy of 89.81% on the held-out test set.
* The Lasso model achieved a macro F1-score of 0.90.
* The baseline and Ridge models produced the same accuracy of 87.96% in this evaluation.
* The classification report shows the precision, recall, and F1-score for both turnover classes.

📋 Evaluation Metrics

The models were evaluated using:

* Accuracy — proportion of correctly classified samples.
* Precision — proportion of predicted positive cases that were actually positive.
* Recall — proportion of actual positive cases correctly identified.
* F1 Score — harmonic mean of precision and recall.
* Confusion Matrix — used to analyze correct and incorrect classifications.

📂 Project Structure

employee-turnover-prediction/
│
├── employee_turnover_model.ipynb
├── employee_turnover.csv
└── README.md

