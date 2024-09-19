# Bank Customer Churn

## Why it Matters:
Customer attrition is a critical problem for financial institutions, as it is more expensive to acquire new customers than to retain existing ones. By predicting which customers are likely to churn, the bank can implement **targeted retention strategies**, **proactive customer engagement**, **real-time churn alerts**, **improving customer retention** and **reducing revenue losses**.

## Business Problem Summary:
To predict **customer attrition** (churn) based on various **categorical** and **numerical** attributes provided by a bank. **Attrition** represents customers who have stopped using the bank’s services. The goal is to identify key drivers of customer attrition and build a predictive model to proactively address churn risks.

## Key Business Questions:
1. **What factors contribute to customer attrition?**
2. **Can we predict customers at risk of attrition using demographic and behavioral data?**
3. **How can the bank reduce customer churn based on these insights?**

## Steps:
1. **Business Problem Formulation (Part1)**
2. **Data Collection (Part1)**
3. **Data Processing and Manipulation (Part1)**
4. **EDA Insights(Part1)**
5. **Predictive model to classify customers as either "attrited" or "non-attrited (Part 2).**
6. **Model Evaluation and Interpretation(Part2).**
7. **Recommendation**
---

## Dataset Overview

| Column                  | Type                   | Description                                                            |
|-------------------------|------------------------|------------------------------------------------------------------------|
| CLIENTNUM               | Identifier             | Unique identifier for each customer                                     |
| Attrition_Flag           | Categorical (Target)   | Indicates if a customer is attrited (churned)                           |
| Customer_Age             | Numeric                | Age of the customer                                                    |
| Gender                   | Categorical            | Gender of the customer                                                 |
| Dependent_count          | Numeric                | Number of dependents the customer has                                  |
| Education_Level          | Categorical            | Customer’s level of education                                          |
| Marital_Status           | Categorical            | Marital status of the customer                                         |
| Income_Category          | Categorical            | Customer’s income category                                             |
| Card_Category            | Categorical            | Credit card category held by the customer                              |
| Months_on_book           | Numeric                | Number of months the customer has been with the bank                   |
| Total_Relationship_Count | Numeric                | Number of bank products the customer holds                             |
| Months_Inactive_12_mon   | Numeric                | Number of months in the past year the customer has been inactive        |
| Contacts_Count_12_mon    | Numeric                | Number of contacts the customer had with the bank in the past year      |
| Credit_Limit             | Numeric                | Maximum credit limit on the customer’s card                            |
| Total_Revolving_Bal      | Numeric                | Total balance carried over month-to-month                              |
| Avg_Open_To_Buy          | Numeric                | Average available credit                                               |
| Total_Amt_Chng_Q4_Q1     | Numeric                | Percentage change in transaction amount from Q4 to Q1                  |
| Total_Trans_Amt          | Numeric                | Total transaction amount                                               |
| Total_Trans_Ct           | Numeric                | Total count of transactions                                            |
| Total_Ct_Chng_Q4_Q1      | Numeric                | Percentage change in transaction count from Q4 to Q1                   |
| Avg_Utilization_Ratio    | Numeric                | Ratio of balance to credit limit (credit utilization)                  |
