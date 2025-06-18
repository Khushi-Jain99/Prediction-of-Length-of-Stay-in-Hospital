# Prediction-of-Length-of-Stay-in-Hospital
This machine learning project aims to predict the **Length of Stay (LOS)** of patients in a hospital based on clinical, demographic, and admission-related data. Predicting LOS accurately helps hospitals in **resource allocation, bed management, and operational planning**.

## Problem Statement

Hospitals often face challenges in managing resources due to uncertainty in patient discharge timelines. The goal of this project is to develop a model that predicts how long a patient is likely to stay in the hospital, using structured patient data at the time of admission.

## Objectives
- Perform **data preprocessing** and **feature engineering** to handle medical and categorical variables.
- Evaluate different machine learning algorithms and choose the best-performing one.

## Dataset
- **Source:** Kaggle 
- **Sample Features:**
  - Age, Gender, Diagnosis, Severity of Illness
  - Type of Admission, Department
  - Previous Admissions

## Workflow
1. **Data Cleaning**
   - Remove null values, handle outliers
2. **Feature Engineering**
   - Convert categorical variables using encoding
   - Normalize numeric features
3. **Model Building**
   - Try multiple classifiers: Logistic Regression, Decision Tree, Random Forest, XGBoost
4. **Model Evaluation**
   - Accuracy, F1 Score, Confusion Matrix

## 📈 Results

- Achieved **93% accuracy** using Naive Bayes
- Confusion matrix showed high precision for short and medium stay
