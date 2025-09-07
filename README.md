Credit Scoring Model — CodeAlpha Internship Task 1
**Project Overview**
This project is part of the CodeAlpha Machine Learning Internship, designed to provide hands-on experience in building real-world ML solutions. The goal of this task is to develop a Credit Scoring Model that predicts an individual's creditworthiness based on historical financial and demographic data.

**Objective**
To build a classification model that accurately predicts whether a person is creditworthy using features such as income, debt, credit score, loan details, and personal attributes.

**Dataset**
I used a dataset from Kaggle.
The dataset used contains the following columns:

Age, Gender, Education, Income, Debt, Credit_Score, Loan_Amount, Loan_Term, Num_Credit_Cards, Payment_History, Employment_Status, Residence_Type, Marital_Status, Creditworthiness

Additional engineered features:

debt_to_income = Debt / Income

loan_to_income = Loan_Amount / Income

 **Tools & Technologies**
Google Colab — development environment

Python — programming language

Pandas & NumPy — data manipulation

Scikit-learn — preprocessing, modeling, evaluation

Matplotlib & Seaborn — visualization

Joblib — model saving

**Workflow Summary**
Data Loading: Imported dataset from Google Drive into Colab.

Exploratory Analysis: Inspected data structure and feature types.

Feature Engineering: Created new financial ratios to improve model performance.

Preprocessing:

Imputed missing values

Scaled numerical features

One-hot encoded categorical features

Modeling:

Used a Random Forest Classifier

Applied GridSearchCV for hyperparameter tuning

Evaluation:

Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC

Visuals: Confusion Matrix and ROC Curve

Model Saving: Exported trained model to Google Drive for future use.

**Results**
Achieved strong classification performance with balanced precision and recall.

ROC-AUC score indicated high model reliability in distinguishing creditworthy vs. non-creditworthy individuals.
