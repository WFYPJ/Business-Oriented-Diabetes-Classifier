# Business-Oriented Diabetes Classifier

This project builds a business-focused machine learning classifier to predict diabetes in patients, using the popular Pima Indians Diabetes Dataset.

## 📊 Project Overview

- **Goal:** Develop a predictive model that balances medical accuracy and business application (cost-benefit analysis).
- **Dataset:** [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Main Tasks:**
  - Data cleaning and exploration
  - Feature selection and engineering
  - Model training (Logistic Regression, Random Forest, XGBoost)
  - Model evaluation (accuracy, precision, recall, F1-score, ROC-AUC)
  - Business interpretation: Which model provides the best balance between medical outcomes and business constraints?

## 🛠 Tools & Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn
- Jupyter Notebook

## 🔍 Key Results

- Best model: Random Forest (with ROC-AUC: X.XX)
- Key insights:
  - Feature importance: Glucose, BMI, Age are top predictors.
  - Business implication: Prioritizing sensitivity reduces risk of missing positive cases but increases false positives.

## 📂 Files

- `diabetes_classifier.ipynb`: Main notebook with full code and analysis.

## 💡 What I Learned

- End-to-end machine learning workflow, from raw data to actionable insights.
- How to balance machine learning performance with business needs.
- Practical application of model interpretability tools (like feature importance).
