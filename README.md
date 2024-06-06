# E-bike-loan-project

Problem Statement
A bank is facing an increasing incidence of non-payment in their E-bike financing division.
Default rates are adversely impacting the bank's profitability, especially given the high market competition.
Problem Objective
The bank aims to build a credit model based on customer data to predict loan defaults and manage risk effectively.
A successful model will help the bank mitigate default challenges and maintain profitability.
Data Description
The dataset comprises 39 features, categorized as follows:
ID: Identifier for each unique customer.
Default: The target feature (Indicating whether a customer is a defaulter or not).
Independent variables: Examples include salary, residence, job status, number of children, previous loans, automobile possession, and more.
Data Pre-processing Steps and Inspiration
Exploratory Data Analysis (EDA): Conducted to gain insights into the data.
Handling Null Values: Removed null values based on domain knowledge and correlation with the target.
Outlier Identification: Outliers were identified but not removed due to significant impact.
Feature Selection: Used Information Value (IV) analysis for categorical features and Variance Inflation Factor (VIF) for numerical features to mitigate multicollinearity.
Imbalanced Dataset Handling: Techniques like under-sampling, over-sampling, and SMOTE were used to address class imbalance. SMOTE yielded the best results.
Plotting the correlation plot:
Correlation Plot

Choosing the Algorithm for the Project
Given that it's a classification problem, Logistic Regression, Decision Trees, and Random Forest were considered.
Random Forest was chosen due to its performance on the complex dataset.
Model Evaluation and Techniques
As it's an imbalanced dataset, accuracy alone is not a reliable metric. A classification report focusing on F1 score was used.
The Random Forest model achieved an F1 score of approximately 96% for both classes.
ROC Curve for Random Forest Model
ROC Curve

References
Leveraged knowledge from previous classification projects.
Utilized online resources, including a YouTube lecture by Code Basics on dealing with imbalanced datasets.
