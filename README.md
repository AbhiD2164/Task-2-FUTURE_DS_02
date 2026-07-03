Customer Retention & Churn Analytics Dashboard using Power BI
Project Overview

This project presents an interactive Customer Retention & Churn Analytics Dashboard developed using Microsoft Power BI. The dashboard analyzes customer behavior, identifies churn patterns, evaluates customer retention, and provides business insights to support data-driven decision-making.

The analysis is based on the IBM Telco Customer Churn Dataset, which contains customer demographics, subscription details, service usage, billing information, and churn status.

Objective

The primary objectives of this project are to:

Analyze customer churn behavior.
Measure customer retention and churn rate.
Identify factors influencing customer attrition.
Segment customers based on demographics and subscription details.
Provide actionable business recommendations to improve customer retention.
Tools & Technologies
Microsoft Power BI Desktop
Power Query Editor
DAX (Data Analysis Expressions)
IBM Telco Customer Churn Dataset
Data Visualization Techniques
Dataset Information

Dataset Name

IBM Telco Customer Churn

Records

7,043 Customers

Attributes

21 Columns
Important Features
Customer ID
Gender
Senior Citizen
Partner
Dependents
Tenure
Phone Service
Internet Service
Online Security
Online Backup
Device Protection
Tech Support
Streaming TV
Streaming Movies
Contract
Paperless Billing
Payment Method
Monthly Charges
Total Charges
Churn
Data Preparation

The following preprocessing steps were performed:

Imported dataset into Power BI.
Removed duplicate records.
Corrected data types.
Handled missing values.
Converted Total Charges into numeric format.
Created calculated columns.
Created DAX measures.
Designed an optimized data model.
Dashboard Pages
1. Executive Dashboard

Provides a high-level overview of customer retention performance.

KPIs
Total Customers
Active Customers
Churned Customers
Churn Rate
Retention Rate
Average Monthly Charges
Average Tenure
Total Revenue
2. Customer Demographics

Analyzes customer characteristics including:

Gender Distribution
Senior Citizens
Partner Status
Dependents
Customer Segmentation
3. Churn Analysis

Examines customer churn using:

Contract Type
Internet Service
Payment Method
Customer Segments
Churn Distribution
4. Revenue Analysis

Provides financial insights including:

Revenue by Contract
Revenue by Customer Type
Revenue by Internet Service
Monthly Charges Analysis
Customer Value Distribution
DAX Measures Used

The report includes several DAX measures, such as:

Total Customers
Active Customers
Churned Customers
Churn Rate
Retention Rate
Average Monthly Charges
Average Tenure
Total Revenue
Key Business Insights

The analysis highlights several important trends:

Customers with month-to-month contracts show significantly higher churn than customers on long-term contracts.
Customers with short tenure are more likely to discontinue services.
Higher monthly charges are associated with increased churn in several customer segments.
Customers using Electronic Check as a payment method exhibit higher churn rates.
Customers without Online Security or Tech Support services are more likely to churn.
Long-term contracts generally demonstrate stronger customer retention.
Business Recommendations

Based on the findings, the following strategies are recommended:

Encourage customers to switch to long-term contracts.
Develop loyalty programs for customers with low tenure.
Offer bundled packages including Online Security and Tech Support.
Improve customer engagement during the initial months of service.
Review pricing strategies for customers with higher monthly charges.
Target high-risk customer segments with personalized retention campaigns.
Features
Interactive dashboards
Dynamic filtering
Drill-down analysis
Customer segmentation
KPI monitoring
Business insights
Executive reporting
Future Enhancements

Potential improvements include:

Predictive churn modeling using Machine Learning.
Real-time data integration.
Automated report refresh using Power BI Service.
Customer Lifetime Value (CLV) analysis.
Cohort analysis.
Customer satisfaction score integration.
AI-powered forecasting.
Project Structure
FI Task-2.pbix
│
├── Executive Dashboard
├── Customer Demographics
├── Churn Analysis
├── Revenue Analysis
└── README.md
Learning Outcomes

This project demonstrates practical skills in:

Data Cleaning
Data Transformation
DAX Calculations
Data Modeling
Interactive Dashboard Development
Customer Analytics
Business Intelligence
Data Visualization
KPI Design
Decision Support Analytics
Author

Abhinav Dwivedi

Data Science & Analytics Enthusiast

License

This project is created for educational, internship, and portfolio purposes only.