# Task 4: Loan Default Risk with Business Cost Optimization

## Task Objective

The objective of this project is to predict the likelihood of loan default using machine learning models and optimize the decision threshold based on business cost analysis. The project compares Logistic Regression and CatBoost models to support better loan approval decisions.

---

## Your Approach

- Loaded and explored the Home Credit Default Risk dataset.
- Cleaned missing values and preprocessed the data.
- Encoded categorical features using Label Encoding.
- Applied feature scaling using StandardScaler.
- Split the dataset into training and testing sets.
- Trained two binary classification models:
  - Logistic Regression
  - CatBoost
- Evaluated the models using Accuracy, Confusion Matrix, Classification Report, and ROC-AUC.
- Defined business costs for False Positives and False Negatives.
- Optimized the decision threshold to minimize total business cost.
- Performed feature importance analysis using CatBoost.

---

## Results and Findings

- Successfully built two binary classification models for loan default prediction.
- CatBoost provided better predictive performance than Logistic Regression.
- Business cost optimization identified the threshold that minimized the total financial risk.
- Feature importance analysis highlighted the most influential variables affecting loan default prediction.
- The optimized threshold can help financial institutions make more cost-effective lending decisions.
