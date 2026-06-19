CUSTOMER CHURN ANALYSIS USING PYTHON

Project Overview


Customer churn is one of the most critical challenges faced by subscription-based businesses. Acquiring new customers is often more expensive than retaining existing ones, making customer retention a key business objective.
This project performs an Exploratory Data Analysis (EDA) on a telecom customer dataset to identify the major factors contributing to customer churn. Through data cleaning, visualization, and business-focused analysis, the project uncovers patterns that can help organizations improve customer retention strategies.

Objectives :-


Analyze customer churn behavior.

Identify customer segments with high churn risk.

Understand the impact of demographics, tenure, contracts, services, and payment methods on churn.

Generate actionable business insights to improve customer retention.



Dataset Information :-


The dataset contains customer information including:

Customer demographics

Account information

Contract details

Internet and phone services

Additional support services

Payment methods

Customer churn status



Key Features :-


Feature Category

Columns

Demographics

Gender, SeniorCitizen

Customer Relationship

Tenure, Contract
Services
PhoneService, InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport
Entertainment Services
StreamingTV, StreamingMovies
Billing Information
PaymentMethod, TotalCharges
Target Variable
Churn



Tools & Libraries Used :-


Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook



Data Cleaning & Preprocessing :-


The following preprocessing steps were performed:-

Replaced blank values in the TotalCharges column with 0.

Converted TotalCharges from object to float datatype.

Checked for null values and duplicates.

Converted SeniorCitizen values from 0/1 to Yes/No for better interpretability.



Exploratory Data Analysis :-

The following visualizations were created:-

1. Churn Distribution :-
Count Plot
Pie Chart


2. Demographic Analysis :-
   
Gender vs Churn
Senior Citizen vs Churn


3. Customer Relationship Analysis :-
   
Tenure Distribution by Churn
Contract Type vs Churn


4. Service Analysis :-


Phone Service

Multiple Lines

Internet Service

Online Security

Online Backup

Device Protection

Tech Support

Streaming TV

Streaming Movies


5. Payment Method Analysis :-
   
Churn by Payment Method



Key Insights :-

Customer Churn Overview

Approximately 26.54% of customers have churned.

Around 73.46% of customers have been retained.



Demographic Insights :-

Gender has minimal impact on customer churn.

Senior Citizens exhibit a higher churn rate than non-senior customers.



Tenure Analysis :-

Customers with shorter tenure show significantly higher churn.

Long-term customers are more likely to remain with the company.



Contract Analysis :-

Month-to-Month customers are the most likely to churn.

Customers with One-Year and Two-Year contracts demonstrate stronger retention.



Internet Service Analysis :-


Fiber Optic customers show the highest churn rate.

DSL customers are comparatively more stable.

Security & Support Services



Customers without the following services exhibit substantially higher churn:-

Online Security

Online Backup

Device Protection

Tech Support



Streaming Services :-

Streaming TV and Streaming Movies show a relatively weak relationship with churn.

Entertainment services alone do not significantly impact customer retention.



Payment Method Analysis :-

Customers using Electronic Check exhibit the highest churn rate.

Automatic payment methods are associated with stronger retention.



High-Risk Customer Profile :-

The analysis identifies the following characteristics as common among churned customers:

Senior Citizen

Short customer tenure

Month-to-Month contract

Fiber Optic internet service

No Online Security

No Online Backup

No Device Protection

No Tech Support

Electronic Check payment method



Business Recommendations :-

Improve customer onboarding during the first year.

Encourage migration to longer-term contracts.

Investigate the causes of churn among Fiber Optic customers.

Bundle support and security services with internet plans.

Promote automatic payment methods.

Create targeted retention campaigns for high-risk customer segments.




Project Structure :-

Customer-Churn-Analysis/

│
├── Customer Churn Analysis.ipynb

├── Customer Churn.csv

├── README.md

└── Visualizations/




Conclusion :-

The analysis demonstrates that customer churn is primarily driven by tenure, contract type, internet service category, support-service adoption, and payment method. Customers receiving greater service value and maintaining longer contractual relationships are significantly more likely to remain loyal. These findings can help businesses develop targeted retention strategies and improve long-term customer profitability.



Author-

Shivoy Jain

Aspiring Data Analyst | SQL | Python | Power BI | Excel

Feel free to connect, provide feedback, or contribute to the project.

