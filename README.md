# Breast Cancer Classification  
Supervised Machine Learning for Medical Diagnosis

## Introduction

This project implements a machine learning classification system to detect breast cancer using the Breast Cancer Wisconsin dataset from scikit-learn. The goal is to classify tumors as malignant or benign based on diagnostic features extracted from digitized images.

## Objective

The objective of this project is to:

- Build and compare classification models  
- Evaluate their predictive performance  
- Identify the most effective model for accurate medical diagnosis  

## Dataset

- Total Samples: 569  
- Features: 30 numerical features describing tumor characteristics  
- Target Variable:
  - 0 → Malignant  
  - 1 → Benign  

## Data Preprocessing

- Performed train-test split (80/20)  
- Applied feature scaling using StandardScaler  
- Ensured consistent transformation of training and testing data  

Feature scaling was necessary to improve convergence and performance, particularly for Logistic Regression.

## Exploratory Data Analysis

- Verified dataset shape and feature count  
- Examined class distribution  
- Evaluated model outputs using:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
  - Confusion Matrix  

## Model Building

Two classification models were implemented:

### Logistic Regression
- Maximum iterations increased to ensure convergence  
- Achieved high classification accuracy (~97%)

### Random Forest Classifier
- Ensemble-based model with 100 decision trees  
- Achieved strong performance (~96%)  
- Confusion matrix visualized for performance interpretation  

## Conclusion

Both Logistic Regression and Random Forest demonstrated strong predictive performance on the dataset. Logistic Regression slightly outperformed Random Forest in overall accuracy. This project highlights the effectiveness of supervised learning algorithms in medical diagnosis classification tasks.
