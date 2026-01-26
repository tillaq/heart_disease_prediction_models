# Heart Disease Prediction using Baseline Models (Logistic Regression & SVM)

## Overview
This repository contains my individual contribution to a course project on predicting heart disease using supervised learning.  
The focus here is on building and evaluating baseline classification models; Logistic Regression and Support Vector Machine (SVM with RBF kernel) that estimate heart disease risk from clinical and lifestyle features, helping identify high‑risk patients for earlier intervention and preventive care.

> The full project was completed by a 3‑member team.  
> This repository includes **only the code, analysis, and results that I personally implemented**.​

## Dataset
- Source: Heart Disease dataset in CSV form, downloaded from Kaggle.​ (https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset?resource=download)
- Features: 13 clinical attributes (e.g., age, sex, trestbps, chol, thalach, cp, exang, oldpeak, slope, ca, thal).​
- Target:
0 → no heart disease, 1 → heart disease.

## Tools and Libraries Used
- Language: Python (Visual Studio Code)
- Libraries:
    - pandas and numpy for data handling
    - scikit-learn for model training, preprocessing, and evaluation
    - matplotlib and seaborn for exploratory data analysis and plots
- Techniques:
  - Loading and inspecting the dataset
  - Handling missing values and basic cleaning
  - Train–test split
  - Feature scaling with StandardScaler for logistic regression and support vector machine
  - Training Logistic Regression and SVM classifiers using scikit‑learn
  - Evaluating models with:
      - Accuracy
      - Confusion matrix
      - Precision, recall, F1‑score
      - ROC curve and ROC–AUC
  - Plotting performance metrics and ROC curves

Metrics: accuracy_score, precision_score, recall_score, f1_score, roc_auc_score, confusion_matrix, classification_report, roc_curve.

## Results
- Logistic Regression metrics:
  - Accuracy: 0.810
  - Precision: 0.762
  - Recall: 0.914
  - F1‑score: 0.831
  - ROC–AUC: 0.930

- Support Vector Machine (SVM) metrics:
  - Accuracy: 0.927
  - Precision: 0.917
  - Recall: 0.943
  - F1‑score: 0.939
  - ROC–AUC: 0.977

- SVM (RBF) achieved higher accuracy and ROC–AUC than Logistic Regression on the test set.  
- Logistic regression remains more interpretable via coefficients, while SVM provided the best predictive performance in this baseline setup.  
- Both models showed strong recall, indicating good sensitivity to heart disease cases.
