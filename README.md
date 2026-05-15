# Customer Churn Analysis

## Project Overview
This Project focuses on analyzing customer churn behavior in a telecom company using SQL and Pyhon. The main objective of the project is to identify factors affecting customer churn and generate business insights that can help improve customer retention.

---


## Objectives
- Analyze ustomer churn patterns
- Identify high-risk customer segments
- Perform visulization using Python.
- Generate business recommendations for retention strategies.

---

## Tools and Technologies Used
- Python
- Pandas
- Matplotlib
- MySQL
- SQL
- Jupyter Notebook
- VS Code

## Workflow
1. Imported Dataset into MySQL database.
2. Performed SQL queries for analysis.
3. Connected MySQL qith Python using mysql-connector
4. Laded SQL Query results into pandas DataFrames
5. Created Visualizations using Matplotlib.
6. Generated business insights and recommendation.

---

## Feature Engineering
Creted a new feature called 'TenureGroup' to categorize customers into:
- New Customer
- Mid-Term Customer
- Long-Term Customer

This helped me analyze churn behaviour based on customer lifecycle stages.

---

## Key Insights
- Customers with month-to-month contracts showed the highes churn rates.
- Long-term customers had significantly lower churn rates.
- Fiber optics internet users exhibites higher churn percentages.
- Electronic check users showed higher churn compared to automatic payment users.
- Higher-risk churn segements included customers using month-to-month contracts with fiber optic services.

---

## Business Recommendation
- Promote long-term contracts through discounts and incentives.
- Imporve onboarding and retention strategies for new customers.
- Investigate customer dissatisfaction relates to fiber optic services.
- Encourage customers to adopt utomatic payment methods.
- Target high risk customer segements with retention campaigns.


# Visualizations

## Churn Percentage by Contract Type
![Contract Churn](images/Churn_Percentage_By_Contract_Type.png)

---

## Churn Percentage by Tenure Group
![Tenure Group Churn](images/Churn_Percentage _by_Tenure_Group.png)

---

## Churn Percentage by Contract and Internet Service
![Contract Internet Churn](images/Churn_Percentage_by_Contract_and_Internet_Service.png)

---

## Churn Percentage by Payment Method and Contract
![Payment Contract Churn](images/Churn_Percentage_by_Payment_Method_and_Contract.png)

---

## PRojects Structure

```text
Customer-Churn-Analysis/
│
├── data/
│    └── raw
│         └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
│── Images/
│   ├── churn_percentage_by_tenure_group.png
│   ├── churn_percentage_by_contract_and_internet_service.png
│   ├── churn_percentage_By_contract_type.png
│   └── churn_percentage_by_payment_method_and_contract.png
│
├── notebooks/
│   └── customer_churn_analysis.ipynb
├── visuals/
├── README.md
└── requirements.txt