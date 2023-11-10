# MachineLearning

## This repository is for Credit Card Fraud Detection project

### Group Memebers: Shri Abhiraami Thangavel, Addison Golo, Moyurakshi Saha

### Introduction
Credit card fraud is a pervasive issue that affects millions of people worldwide. With the increasing reliance on digital transactions, the frequency and sophistication of fraudulent activities have also risen. Our project revolves around the analysis of a comprehensive Credit Card Fraud dataset from Kaggle, motivated by the imperative to mitigate financial losses and enhance the security of online transactions.

### Problem Statement
#### Goal 1 : Predictive Modeling for Fraud Detection
Research Question: Can we develop a machine learning model that accurately predicts whether a given transaction is fraudulent based on the provided features?
Sub-Goals:
Evaluate the performance of various classification algorithms.
#### Goal 2: Feature Importance and Relevance
Research Question: Which features are most indicative of a fraudulent transaction?
Sub-Goals:
Utilize feature importance techniques to identify key predictors of fraud.

### Methodology
Our primary algorithm will be logistic regression, a widely used method for binary classification tasks. Given the nature of fraud detection (a binary outcome - fraudulent or not), logistic regression is well-suited for this scenario. Additionally, we plan to implement a secondary model using Random Forest with decision trees. This will enable us to conduct a variable importance analysis, aiding in understanding the key features influencing fraud detection.

### Dataset
The primary objective of this dataset is to facilitate the development of fraud detection algorithms and models to identify potentially fraudulent transactions.
- Time: The time of the transaction
- V1-V28: Anonymized features representing various transaction attributes (e.g., time, card#,acct#,merchant name,location, currency, country code etc.)
- Amount: The transaction amount
- Class: Binary label indicating whether the transaction is fraudulent (1) or not (0)

### Plan of Work
- Data Exploration and Understanding: Gain insights into the dataset, understand its features, and explore relationships among variables.
- Data Preprocessing: Address missing data, perform data cleansing, and apply transformations such as normalization and log transformations.
- Model Implementation: Utilize logistic regression and Random Forest algorithms for predictive modeling.
- Variable Importance Analysis: Investigate and interpret significant variables through Random Forest decision trees.
- Analysis and Results: Present findings on significant variables, model performance, and interesting discoveries.
- Discussion: Reflect on the challenges faced during data cleansing, missing data handling, and the impact of data transformations on model outcomes.

### Potential Application/Use Case
- Credit Card Fraud Detection: Build machine learning models to detect and prevent credit card fraud by identifying suspicious transactions based on the provided features.
- Merchant Category Analysis: Examine how different merchant categories are associated with fraud.
- Transaction Type Analysis: Analyze whether certain types of transactions are more prone to fraud than others.

### Expected Results
We anticipate developing a robust logistic regression model for fraud detection with at least 90% accuracy, complemented by insights from the Random Forest model regarding key features influencing fraud. Additionally, our project aims to uncover interesting patterns and contribute to the understanding of credit card fraud detection methodologies.

This project aligns with the real-world challenges faced by financial institutions and serves as an excellent opportunity to apply machine learning techniques to solve practical problems.

### Reference
Kaggle
ChatGPT
