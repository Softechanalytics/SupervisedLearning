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
<ul>
<li>Python</li>

<li>Pandas, NumPy</li>

<li>Matplotlib, Seaborn</li>

<li>Scikit-learn</li>

<li>Jupyter Notebook</li>
</ul>

## 🔍 Project Workflow
### 1. Data Preprocessing
<ul>
<li>Loaded and explored the dataset</li>

<li>Checked for missing/null values</li>

<li>Summarized data statistics and correlations</li>
</ull>
### 2. Exploratory Data Analysis (EDA)
<ul>
<li>Distribution of categorical and numerical features</li>

</li>Count of customers with:</li>
<ul>
<li>No mortgage</li>

<li>No credit card usage</li>
</ul>
<li>Univariate and bivariate visualizations</li>
</ul>

### 3. Data Preparation
<ul>
<li>Feature selection</li>

<li>Categorical encoding (if applicable)</li>

<li>Feature scaling</li>
</ul>

### 4. Model Training
<ul>
<li>Split dataset into 70% training and 30% test</li>

<li>Trained a Logistic Regression model</li>

<li>Evaluated using:</li>
<ul>
<li>Accuracy</li>

<li>Confusion Matrix</li>

<li>Precision, Recall, F1-score</li>

<li>ROC-AUC curve</li>
</ul></ul>

### 5. Model Optimization
<ul>
<li>Analyzed performance bottlenecks</li>

<li>Suggestions made for hyperparameter tuning, feature engineering, and alternative models</li>
</ul>

### 6. Business Insight
<ol>
<li>Identified key attributes influencing loan acceptance:</li>
<ol>
<li>Income</li>

<li>Education level</li>

<li>CD account ownership</li>
</ol>
<li>Business can now focus campaigns on high-probability segments</li>
</ol>

## 📈 Results
Metric	                                Score
Accuracy:              	                XX.XX%
Precision:                            	XX.XX%
Recall:                                	XX.XX%
F1-Score:                              	XX.XX%
ROC-AUC:                              	XX.XX
(Update with actual values after model evaluation)

## 🚀 Future Improvements
<ol>
<li>Apply advanced models: Random Forest, XGBoost</li>

<li>Perform hyperparameter tuning</li>

<li>Address class imbalance with SMOTE or weighted loss</li>

<li>Deploy as a Flask/Django web app for business use</li>
</ol>

## 📂 Repository Structure
pgsql
Copy
Edit
├── AIML Project 2  Supervised Learning by Chukwuemeka Isaac Anyakwu.ipynb
├── Project SUL- Bank Loan_solution.ipynb
├── Bank_Personal_Loan_Modelling.csv
├── Problem Statement - Thera Bank Personal Loan Modelling Project.pdf
├── README.md

## 🙌 Acknowledgments
This project is part of the Great Learning AIML Program and aims to build proficiency in supervised learning for real-world business problems.

