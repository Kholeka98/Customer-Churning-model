# Customer Churning model

## Project Objective
Develop a machine learning model to accurately predict customer churn in a telecommunications company. By analyzing customer demographic information, service usage patterns, and historical churn data, the goal is to identify factors contributing to churn and build a predictive model that can proactively identify at-risk customers. The ultimate objective is to help the company reduce churn rates, improve customer retention, and enhance overall business profitability.

## About Data
The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). The dataset contains details on customers who have recently stopped using the service (churned) along with the services they subscribed to, such as phone, internet, online security, etc. It also includes account information like customer tenure, contract type, payment method, billing preferences, and financial details such as monthly and total charges. Additionally, demographic information such as gender, age group, and whether they have partners or dependents is provided.

## Strategy
### 1. Exploratory Data Analysis (EDA):
- Understand the dataset's structure, relationships, and patterns.
- Examine distributions, correlations, and outliers.
- Gain insights into potential factors influencing the target variable (churn).

### 2. Feature Selection:
- Identify a subset of relevant features that are most predictive or influential.
- Inform feature selection decisions based on insights from EDA.

### 3. Model Training and Evaluation:
- Select appropriate machine learning algorithms for the classification task (e.g., logistic regression, random forest, support vector machine, and Decision Tree).
- Train the models on the selected features.
- Evaluate model performance using metrics such as accuracy.

### 4. Iterative Process:
- Iterate between feature selection, model training, and evaluation based on results and insights gained.
- Ensure transparency and interpretability of the final model.
- Utilize confusion matrix analysis to further assess model performance, including true positives, true negatives, false positives, and false negatives.


  ## Summary of Result
  1. Logistic Regression:  
    - Accuracy 79.19%
  
2. Random Forest:  
    - Accuracy 78.15%,

3. Support Vector Machine:  
    - Accuracy 79%,

4. DecisionTrees:
    - Accuracy 71.56%,
  
