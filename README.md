# 📊 Customer Churn Analysis & Prediction

## 🧠 Project Overview
Customer churn is a critical challenge for subscription-based businesses. This project focuses on analyzing customer behavior, identifying churn patterns, and predicting customers at risk of churning using SQL, Power BI, and Machine Learning (Random Forest).

The project is divided into two major parts:
1. Churn Analysis (Descriptive Analytics)
2. Churn Prediction (Predictive Analytics)

Interactive dashboards are built in Power BI to deliver business-ready insights.

---

## 🎯 Objectives
- Analyze customer churn trends and key drivers
- Identify high-risk customer segments
- Build a machine learning model to predict churn
- Visualize predicted churners in Power BI
- Demonstrate an end-to-end data analytics workflow

---

## 🛠️ Technologies Used

### 🔹 Data Engineering & Cleaning
- SQL  
  - ETL (Extract, Transform, Load) process  
  - Data cleaning and preprocessing  
  - Handling missing values and duplicates  
  - Feature engineering for analytics and ML  

### 🔹 Data Visualization
- Power BI  
  - Interactive dashboards  
  - DAX measures and calculated columns  
  - Filters, slicers, and drill-downs  
  - KPI-based business insights  

### 🔹 Machine Learning
- Random Forest Classifier  
  - Churn prediction model  
  - Feature importance analysis  
  - Predicted results integrated into Power BI  

---

## 📂 Dataset Description
The dataset contains customer-level information including:
- Demographics (Gender, Age Group, Marital Status)
- Account details (Tenure, Contract Type, Payment Method)
- Service usage (Internet Type, Streaming, Security, Support)
- Financial metrics (Monthly Charges, Revenue, Refunds)
- Target variable: Churn

---

## 🔄 Project Workflow

1. Data Extraction  
   - Raw customer data extracted and loaded into SQL  

2. Data Cleaning & Transformation (SQL)  
   - Removed inconsistencies and null values  
   - Standardized categorical fields  
   - Created tenure groups and churn indicators  

3. Exploratory Data Analysis  
   - Analyzed churn trends by demographics, geography, and services  

4. Power BI Dashboard – Churn Analysis  
   - KPI summary and churn distribution  
   - Customer segmentation and trend analysis  

5. Machine Learning – Churn Prediction  
   - Random Forest model trained on cleaned data  
   - Generated churn predictions  

6. Power BI Dashboard – Churn Prediction  
   - Visualization of customers at risk  
   - Risk profiling by tenure, age, and geography  

---

## 📊 Dashboards

### 🔹 Churn Analysis – Summary Dashboard
Key metrics and insights:
- Total Customers: 3,195  
- Churned Customers: 849  
- Churn Rate: 27%  

Churn analysis by:
- Gender
- Age group
- Payment method
- Contract type
- Tenure group
- Internet service
- State

---

### 🔹 Churn Prediction Dashboard
Highlights:
- Predicted churners: 378 customers
- Risk analysis by:
  - Gender
  - Age group
  - Marital status
  - Tenure
  - Payment method
  - Contract type
  - Geography
- Detailed “Customers at Risk” table for targeted actions

---

## 🤖 Machine Learning Model
- Algorithm: Random Forest Classifier  
- Reason for selection:
  - Handles non-linear relationships
  - Performs well on mixed data types
  - Reduces overfitting compared to single decision trees

- Output:
  - Binary churn prediction (Yes/No)
  - Prediction results visualized in Power BI

---

## 📈 Key Business Insights
- Month-to-month contracts show the highest churn
- Fiber optic users have higher churn rates
- Short-tenure customers are more likely to churn
- Customers without bundled services show higher risk
- Certain states consistently contribute more to churn

---

## 👩‍💻 Author
Surbhi Deshmane  
Aspiring Data Analyst  

Skills: SQL | Power BI | Data Analysis | Machine Learning | ETL  

This project demonstrates an end-to-end data analytics pipeline from raw data to predictive insights.
