# Problem_Set_One

# Customer Churn Analysis Report

## Introduction
This report presents an analysis of customer churn for a subscription-based service. The goal is to understand the factors that contribute to customer attrition and provide insights to reduce churn rates.

## Section 1: Data
The data used for this analysis consists of customer records, including demographics, usage patterns, and churn status.

### Data Description
The dataset contains information on 5,000 customers, with the following features:
- Customer ID
- Customer Age
- Subscription Plan Type
- Monthly Usage
- Customer Tenure (Months)
- Churn Status (1 for Churned, 0 for Retained)

### Data Preprocessing
Data preprocessing steps included:
- Handling missing values
- Encoding categorical features
- Scaling numerical features

## Section 2: Analysis
In this section, we present our analysis and findings related to customer churn.

### Analysis 1: Exploratory Data Analysis
We conducted exploratory data analysis (EDA) to gain insights into the dataset:
- Visualized customer demographics and churn rates
- Examined correlations between features
- Investigated the distribution of monthly usage

### Analysis 2: Churn Prediction Model
We built a machine learning model to predict customer churn using a logistic regression approach:
- Trained the model on a portion of the dataset
- Evaluated model performance using accuracy and confusion matrix

## Section 3: Conclusion
Our analysis revealed several key findings:

- Customers with shorter tenure are more likely to churn.
- Subscription plan type influences churn rates.
- Monthly usage is a strong predictor of churn.

## Section 4: Recommendations
Based on our findings, we recommend the following strategies to reduce churn:

- Implement customer retention programs for new subscribers.
- Offer personalized plans to long-term customers.
- Monitor and proactively reach out to customers with low monthly usage.

## Section 5: Future Work
Future work could involve:

- Exploring additional features, such as customer support interactions.
- Developing more advanced predictive models.
- Continuously monitoring and updating churn prevention strategies.

## References
- [Subscription Service Dataset](https://example.com/dataset)
- [Scikit-learn documentation](https://scikit-learn.org/)
- [Seaborn documentation](https://seaborn.pydata.org/)

---

*Jorge Zamorano* \
*Date: October 4, 2023*
