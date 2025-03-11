# Customer Churn Analysis Dashboard - Power BI Project

## 1. Project Overview
The Customer Churn Analysis Dashboard is an interactive Power BI solution designed to analyze customer attrition for a telecom company. The dashboard provides insights into key factors affecting churn, helping stakeholders make data-driven decisions to enhance customer retention.

## 2. Objectives
- Identify key customer segments with high churn rates.
- Analyze the impact of demographics, subscription tenure, payment methods, and contract types on churn.
- Provide actionable insights to reduce customer churn and improve business performance.
- Showcase advanced Power BI skills, including data modeling, calculations, and visualization.

## 3. Data Source
The dataset used in this project contains customer information, including:
- **Demographics:** Gender, age group (senior citizen, partner, dependents)
- **Subscription Details:** Contract type, tenure, payment methods
- **Billing Information:** Monthly charges, total charges, paperless billing
- **Customer Support Interactions:** Admin and technical support tickets

## 4. Data Cleaning & Transformation
- Imported the dataset into Power BI.
- Cleaned missing and inconsistent data.
- Standardized categorical variables (e.g., Yes/No responses, contract types).
- Created new calculated columns for better insights (e.g., churn risk segmentation).

## 5. Dashboard Components
### **Key Performance Indicators (KPIs)**
- **Total Charges:** $2.86M
- **Monthly Charges:** $139.13K
- **Customers at Risk:** 1869
- **Admin Tickets:** 885
- **Technical Tickets:** 2173

### **Demographics Analysis**
- **Gender Distribution:** Male (50.42%), Female (49.58%)
- **Senior Citizens at Risk:** 25%
- **Partners at Risk:** 36%
- **Dependents at Risk:** 17%

### **Subscription & Churn Analysis**
- **Tenure Impact:** Majority of churned customers had tenure < 1 year (1037 customers).
- **Contract Type Impact:**
  - Month-to-month: Highest churn (1655 customers).
  - One-year and two-year contracts: Lower churn rates.
- **Payment Methods Impact:**
  - Electronic check users show higher churn (1071 customers).
  - Auto-payment methods have lower churn rates.
- **Paperless Billing Impact:**
  - 74.91% of churned customers use paperless billing.

### **Power BI Dashboard**
  <img width="638" alt="image" src="https://github.com/user-attachments/assets/f2709c68-ef30-4b3e-9ddc-fece0bdb59e6" />


## 6. Technical Implementation
- **Data Modeling:**
  - Connected multiple data tables to establish relationships.
  - Created calculated columns and measures.
- **Calculations Used:**
  - Customer Churn Rate = COUNT(Churned Customers) / COUNT(Total Customers)
  - Average Monthly Charges = AVERAGE(MonthlyCharges)
  - Total Churned Revenue = SUM(Churned Customers * Monthly Charges)
- **Visualization Techniques:**
  - Bar charts, pie charts, and KPI indicators for intuitive insights.
  - Filters and slicers for dynamic data exploration.
  - Conditional formatting for highlighting risk areas.

## 7. Insights & Recommendations
- **Improve Retention for New Customers:** Offer incentives and personalized onboarding for customers with tenure < 1 year.
- **Encourage Long-Term Contracts:** Provide discounts or loyalty programs for annual contracts.
- **Promote Auto-Payments:** Incentivize customers to switch to bank transfers or credit card payments to reduce churn.
- **Enhance Customer Support:** Reduce technical issues by improving service quality and response times.

## 8. Key Learnings & Skills Demonstrated
- **Power BI Skills:**
  - Data Import, Cleaning, and Transformation
  - Data Modeling and Relationship Management
  - Calculations and Measures
  - Interactive Visualizations and Dashboards
- **Business Intelligence & Data Analysis:**
  - Customer segmentation and churn analysis
  - Data-driven decision-making
  - Business strategy recommendations

## 9. Future Enhancements
- **Predictive Churn Modeling:** Implement machine learning models to predict customer churn risk.
- **Real-Time Data Updates:** Integrate Power BI with live data sources for real-time monitoring.
- **Drill-Down Analysis:** Add drill-through pages for deeper customer insights.

---
This project effectively showcases Power BI capabilities and analytical skills, making it a strong addition to a professional portfolio.


