# Heart Disease Prediction using Baseline Models (Logistic Regression & SVM)

## Overview
This project focuses on predicting the presence of heart disease using supervised machine learning techniques. I implemented and evaluated baseline classification models; Logistic Regression and Support Vector Machine (SVM) to estimate heart disease risk based on clinical and lifestyle attributes.

> The full project was completed by a 3‑member team.  
> This repository includes **only the code, analysis, and results that I personally implemented**.​

## Dataset
- Source: Heart Disease dataset (Kaggle)​ (https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset?resource=download)
- Features: 13 clinical attributes (e.g., age, sex, trestbps, chol, thalach, cp, exang, oldpeak, slope, ca, thal).​
- Target Variable:
  - `0` → No heart disease  
  - `1` → Heart disease

## Tools and Libraries Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Development Environment:** Visual Studio Code

## Key Tasks Performed
- Loaded and inspected the dataset
- Performed basic data cleaning and handled missing values
- Conducted exploratory data analysis (EDA)
- Applied train–test split
- Scaled features using `StandardScaler`
- Trained baseline classifiers:
  - Logistic Regression
  - Support Vector Machine (RBF kernel)
- Evaluated models using:
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion Matrix
  - ROC Curve and ROC–AUC
 
## Model Performance
### Logistic Regression
- Accuracy: **81.0%**
- Precision: **76.2%**
- Recall: **91.4%**
- F1-score: **83.1%**
- ROC–AUC: **0.93**

### Support Vector Machine (SVM)
- Accuracy: **92.7%**
- Precision: **91.7%**
- Recall: **94.3%**
- F1-score: **93.9%**
- ROC–AUC: **0.98**

**Observation:**  
SVM significantly outperformed Logistic Regression, suggesting the presence of non-linear relationships in the dataset.

## What I Learned
- Practical implementation of classification models using scikit-learn
- Importance of feature scaling for distance-based models
- Evaluating models beyond accuracy using multiple performance metrics
- Interpreting ROC curves and AUC for classification problems
- Comparing linear vs non-linear models in a real-world dataset

## Conclusion
This project strengthened my understanding of supervised learning workflows and model evaluation techniques, while giving hands-on experience with baseline classification models in a healthcare context.
