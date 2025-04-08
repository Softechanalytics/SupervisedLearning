# 💰 Thera Bank Personal Loan Classification
Supervised Machine Learning Project | Classification | Logistic Regression
By Chukwuemeka Isaac Anyakwu

## 📌 Overview
This project focuses on predicting the likelihood of a liability customer opting for a personal loan. Thera Bank wants to improve the targeting strategy of its marketing campaigns, maximizing conversion rates while minimizing campaign costs.

Using customer demographic and behavioral data, we build a logistic regression model to identify potential personal loan buyers.

## 🧠 Problem Statement
Thera Bank aims to convert liability-only customers (e.g., savings/checking accounts) into personal loan customers. A previous campaign yielded a ~9.6% success rate, and the bank wants to use machine learning to improve targeting and efficiency.

## 📊 Dataset
The dataset contains 5,000 customer records with 14 features:
<ul>
<li>Demographics: Age, Experience, Income, ZIP Code, Family, Education, Mortgage</li>

<li>Banking Behavior: CCAvg, Securities Account, CD Account, Online, Credit Card</li>

<li>Target Variable: Personal Loan (1 if accepted, 0 if not)</li>
</ul>

## 🛠️ Tools & Libraries
<ol>
<li>Python</li>

<li>Pandas, NumPy</li>

<li>Matplotlib, Seaborn</li>

<li>Scikit-learn</li>

<li>Jupyter Notebook</li>
</ol>

## 🔍 Project Workflow
### 1. Data Preprocessing
Loaded and explored the dataset

Checked for missing/null values

Summarized data statistics and correlations

2. Exploratory Data Analysis (EDA)
Distribution of categorical and numerical features

Count of customers with:

No mortgage

No credit card usage

Univariate and bivariate visualizations

3. Data Preparation
Feature selection

Categorical encoding (if applicable)

Feature scaling

4. Model Training
Split dataset into 70% training and 30% test

Trained a Logistic Regression model

Evaluated using:

Accuracy

Confusion Matrix

Precision, Recall, F1-score

ROC-AUC curve

5. Model Optimization
Analyzed performance bottlenecks

Suggestions made for hyperparameter tuning, feature engineering, and alternative models

6. Business Insight
Identified key attributes influencing loan acceptance:

Income

Education level

CD account ownership

Business can now focus campaigns on high-probability segments

📈 Results
Metric	Score
Accuracy	XX.XX%
Precision	XX.XX%
Recall	XX.XX%
F1-Score	XX.XX%
ROC-AUC	XX.XX
(Update with actual values after model evaluation)

🚀 Future Improvements
Apply advanced models: Random Forest, XGBoost

Perform hyperparameter tuning

Address class imbalance with SMOTE or weighted loss

Deploy as a Flask/Django web app for business use

📂 Repository Structure
pgsql
Copy
Edit
├── AIML Project 2  Supervised Learning by Chukwuemeka Isaac Anyakwu.ipynb
├── Project SUL- Bank Loan_solution.ipynb
├── Bank_Personal_Loan_Modelling.csv
├── Problem Statement - Thera Bank Persnal Loan Modelling Project.pdf
├── README.md
🙌 Acknowledgments
This project is part of the Great Learning AIML Program and aims to build proficiency in supervised learning for real-world business problems.

