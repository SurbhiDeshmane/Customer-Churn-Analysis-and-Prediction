# Customer-Churn-Analysis-and-Prediction
📊 Customer Churn Analysis & Prediction
🧠 Project Overview
Customer churn is a critical challenge for subscription-based businesses. This project focuses on analyzing customer behavior, identifying churn patterns, and predicting customers at risk of churning using a combination of SQL, Power BI, and Machine Learning (Random Forest).
The project is divided into two major parts:

Churn Analysis (Descriptive Analytics)

Churn Prediction (Predictive Analytics)

Interactive dashboards are built in Power BI to provide business-ready insights and actionable intelligence.

🎯 Objectives

Understand customer churn trends and drivers

Identify high-risk customer segments

Build a machine learning model to predict churn

Visualize predicted churners for business decision-making

Demonstrate an end-to-end data analytics workflow

🛠️ Technologies Used
🔹 Data Engineering & Cleaning

SQL

ETL (Extract, Transform, Load) process

Data cleaning and preprocessing

Handling missing values, duplicates, and data normalization

Feature preparation for analytics and ML

🔹 Data Visualization

Power BI

Interactive dashboards

DAX measures and calculated columns

Filters, slicers, drill-downs

Business-friendly KPIs

🔹 Machine Learning

Random Forest Classifier

Churn prediction model

Feature importance analysis

Prediction results exported for visualization

📂 Dataset Description

The dataset contains customer-level information including:

Demographics (Gender, Age Group, Marital Status)

Account details (Tenure, Contract Type, Payment Method)

Service usage (Internet type, Streaming, Security, Support)

Financials (Monthly Charges, Revenue, Refunds)

Target variable: Churn

🔄 Project Workflow

Data Extraction

Raw customer data sourced and loaded into SQL

Data Cleaning & Transformation (SQL)

Removed inconsistencies and null values

Standardized categorical variables

Created tenure groups and churn indicators

Exploratory Data Analysis

Churn trends by demographics, geography, services, and payment methods

Power BI Dashboard – Churn Analysis

KPI summary

Customer segmentation

Churn distribution and patterns

Machine Learning – Churn Prediction

Random Forest model trained on cleaned data

Generated predicted churn labels

Identified customers at high risk

Power BI Dashboard – Churn Prediction

Visualization of predicted churners

Risk profiling by age, tenure, state, and services

📊 Dashboards
🔹 Churn Analysis – Summary Dashboard

Key insights include:

Total Customers: 3,195

Churned Customers: 849

Churn Rate: 27%

Churn by:

Gender

Age group

Payment method

Contract type

Tenure group

Internet service

State

📌 Helps identify why customers are leaving.

🔹 Churn Prediction Dashboard

Highlights:

Predicted Churners: 378 customers

Risk distribution by:

Gender

Age group

Marital status

Tenure

Payment method

Contract type

Geography

Detailed “Customers at Risk” table for targeted action

📌 Helps identify who is likely to churn.

🤖 Machine Learning Model

Algorithm: Random Forest Classifier

Why Random Forest?

Handles non-linear relationships well

Works effectively with mixed data types

Reduces overfitting compared to single decision trees

Model Output:

Binary churn prediction (Yes / No)

Prediction results integrated into Power BI for visualization

📈 Key Business Insights

Month-to-month contracts have the highest churn

Fiber optic users show higher churn rates

Short-tenure customers are more likely to churn

Customers without bundled services are at higher risk

Certain states consistently show higher churn probability

🚀 Future Enhancements

Model performance metrics (Accuracy, Precision, Recall, ROC-AUC)

Compare Random Forest with Logistic Regression / XGBoost

Deploy predictions using Python + Streamlit

Automate data refresh in Power BI

Add customer lifetime value (CLV) analysis

👩‍💻 Author

Surbhi Deshmane
Aspiring Data Analyst
Skills: SQL | Power BI | Data Analysis | Machine Learning | ETL

📌 This project demonstrates an end-to-end data analytics pipeline from raw data to predictive insights.
