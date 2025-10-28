# 🩺 Lung Cancer Analysis Project
## Overview

This project focuses on predicting lung cancer outcomes using machine learning techniques for both classification and regression tasks. The main goal is to analyze patient health data and build predictive models that can estimate the likelihood of survival based on multiple clinical and lifestyle factors. By doing this, healthcare professionals can gain valuable insights that could assist in early diagnosis, patient risk assessment, and personalized treatment planning.

## Business and Data Understanding

The key stakeholders for this project include healthcare providers, oncologists, data analysts, and hospital management teams. The dataset used for this analysis contains detailed patient information such as age, BMI, smoking status, cancer stage, family history, and other comorbidities. The primary objective is to use this data to predict the likelihood of lung cancer survival and to understand which factors contribute most significantly to patient outcomes.

The dataset combines both numerical and categorical variables, making it suitable for applying diverse analytical and machine learning techniques.

## Data Preparation

Before modeling, the dataset underwent several preprocessing steps to ensure accuracy and consistency:

  1. Handling missing values using median imputation.

  2. Encoding categorical features (e.g., gender, smoking status, cancer stage) using label encoding.

  3. Scaling numerical features to normalize the data.

  4. Creating additional engineered features, including:

  5. Age Group (categorized as Young, Adult, Senior, Elder)

  6. BMI Category (Underweight, Normal, Overweight, Obese)

  7. Health Risk Score based on hypertension, asthma, cirrhosis, and other cancer indicators.

These steps helped prepare a clean, structured dataset for model training.

## Modeling

Two major modeling tasks were performed in this project:

### 1. Classification Task

A Logistic Regression model was trained to predict patient survival (0 = did not survive, 1 = survived).

The model achieved an accuracy of ~78%, showing strong predictive capability.

The confusion matrix and classification report were used to evaluate precision, recall, and F1-score.

The imbalance in survival data was noted, suggesting potential future improvements with techniques like oversampling or class weighting.

### 2. Regression Task

A Linear Regression model was used to predict continuous outcomes related to lung cancer progression.

Evaluated using RMSE (Root Mean Squared Error) and R² score.

Results showed limited predictive strength, indicating that linear models may not fully capture the complex medical relationships in this dataset.

## Evaluation

Model performance was evaluated using various statistical metrics:

Accuracy & F1-Score for classification

RMSE & R² Score for regression

Confusion Matrix for visualizing prediction outcomes

Data Visualization for exploring feature correlations and survival patterns

The classification model proved more effective than the regression model, making it more suitable for survival prediction.

## Conclusion

This project successfully demonstrated a full data science workflow, from data cleaning and feature engineering to model development and evaluation, applied to a medical dataset.
The Logistic Regression model showed the best performance in predicting patient survival, achieving nearly 78% accuracy.
While the regression task revealed limitations in linear assumptions, both analyses provided valuable insights into the relationships between health indicators and lung cancer outcomes.

These findings highlight the potential for machine learning models to assist in early detection and improve healthcare decision-making. Future improvements could include testing ensemble models like Random Forest or XGBoost, balancing class distribution, and expanding the dataset for more robust predictions.

## Technologies Used

Python

Pandas, NumPy, Scikit-learn

Matplotlib, Seaborn

Jupyter Notebook

Git & GitHub

## Author

Linet Lydia
