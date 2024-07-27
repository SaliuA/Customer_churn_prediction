# Telco Customer Churn Analysis

# 1 Introduction

In today's data-driven world, businesses can enhance efficiency and profitability by leveraging their data to increase revenue and reduce customer churn. This notebook aims to conduct an in-depth analysis of data from a telecommunications company that provides home phone and internet services to 7,043 customers in California. Our goal is to uncover key insights into customer subscription behavior and churn.

### Problem Statement:
In an effort to improve operational efficiency and reduce customer attrition, the telecommunications company seeks to understand the factors influencing customer subscription behavior and churn. By analyzing data from 7,043 customers in California, this study aims to identify key patterns and insights that can inform strategies to increase revenue and minimize customer loss. The primary objective is to develop actionable recommendations that can enhance customer retention and optimize resource allocation.


### In this notebook, we aim to answer several Key Questions for Gaining Insights into Customer Behavior and Churning:

#### Demographic and Customer Information
1. **Demographic Impact on Churn:**
   - How do age and senior citizen status influence churn rates?
   - Does gender play a role in the likelihood of churn?
   - How does having a partner or dependents affect churn?

2. **Location-Based Analysis:**
   - Are there specific states, cities, or zip codes with higher churn rates?
   - How does the geographic location (latitude and longitude) correlate with churn?
   - Do customers in certain regions prefer different types of services (e.g., DSL vs. Fiber Optic)?

#### Service Subscription and Usage Patterns
1. **Service Subscription Trends:**
   - What is the churn rate among customers with different internet service types (DSL, Fiber Optic, Cable)?
   - How do additional services like online security, online backup, and device protection impact churn?
   - Are customers with multiple lines or phone services more or less likely to churn?

2. **Usage Patterns:**
   - How does the tenure (number of months with the company) relate to churn?
   - Do customers who use streaming services (TV and movies) have different churn rates?
   - How does the frequency of website visits correlate with churn?

#### Financial and Contractual Factors
1. **Contract and Billing Preferences:**
   - How do different contract types (Month-to-Month, One Year, Two Year) affect churn?
   - Are customers with paperless billing more or less likely to churn?
   - How do payment methods (Bank Withdrawal, Credit Card, Mailed Check) relate to churn?

2. **Financial Insights:**
   - What is the average monthly charge for customers who churn compared to those who stay?
   - How do total charges influence the likelihood of churn?
   - How does the Customer Lifetime Value (CLTV) correlate with churn rates?

#### Predictive and Behavioral Analysis
1. **Churn Score Analysis:**
   - How accurate is the churn score in predicting actual churn?
   - What are the characteristics of customers with high churn scores?
   - Can we identify patterns in the data that contribute to high churn scores?

2. **Churn Reasons and Patterns:**
   - What are the most common reasons cited by customers for churning?
   - Are there specific services or issues frequently mentioned in churn reasons?
   - Can we identify any trends or commonalities among customers who churn?

By answering these questions, we can develop a comprehensive understanding of customer behavior and the factors driving churn. This, in turn, can inform targeted strategies to enhance customer retention and optimize marketing efforts.

### Objective:
The primary goal of this project is to apply data science techniques to analyze data from the telecommunications company. Our aim is to uncover key patterns in customer behavior and identify factors influencing customer churn. This analysis will provide actionable insights to improve customer retention strategies and develop a predictive model that can accurately identify customers at risk of churning with at least an 80% success rate.

### Data Sources:

The data for this project will be sourced from the telco companies database and will include various attributes such as customer IDs, location,payement method and churn.


### GitHub Project Repository :
* [ShopSmart Data Analysis](https://github.com/SaliuA/telco_Customer_churn)

This project also serves as the project of the month for the Data Community Africa.
* [Data Community Africa](https://www.datacommunityafrica.org//)

### Summary :

Random Forest model obtained a Recall score of 0.83, demonstrating its effectiveness in predicting Customers who would churn. The AUC-ROC score is 0.82, this indicates that the model possess a good level of separability, which means it is adept at distinguishing between churned and non-churned customers, significantly surpassing the threshold of random chance. The base logistic model had a score of 0.59 and 0.72 respectively for recall and AUC-ROC.

### Built With

```
pandas
seaborn
matplotlib
sklearn
```
