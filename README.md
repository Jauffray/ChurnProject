
Telco Customer Churn Analysis Project

Overview:
This project analyzes customer churn at a Telco company to identify the factors that influence churn and provide actionable insights to reduce it. The analysis includes data preprocessing and exploratory data analysis (EDA) to uncover patterns and trends in customer behavior. The results are visualized using Tableau for better interpretation and presentation.

Link the Tableau dashboards: https://public.tableau.com/app/profile/jauffray.bruneton/viz/ChurnProject_17165914665310/ChurnStory?publish=yes

Please check the "Analysis of Customer Churn in Telco Company.pdf" for a nicely presented report of the project.



Table of Contents:
Introduction
Dataset
Usage
Analysis
Results
Recommendations

Introduction:
Customer churn is a critical issue for telecom companies as it directly impacts revenue and growth. This project aims to understand the factors driving customer churn and suggest strategies to improve customer retention.

Dataset:
The dataset used in this analysis contains information on 7,043 customers, with 21 columns capturing various attributes, including demographic information, service subscriptions, payment details, and churn status.
Key columns:
customerID: Unique identifier for each customer.
gender: Gender of the customer (Male, Female).
SeniorCitizen: Indicates if the customer is a senior citizen (1) or not (0).
Partner: Whether the customer has a partner (Yes, No).
Dependents: Whether the customer has dependents (Yes, No).
tenure: Number of months the customer has stayed with the company.
PhoneService: Whether the customer has phone service (Yes, No).
MultipleLines: Whether the customer has multiple lines (No, Yes, No phone service).
InternetService: Type of internet service (DSL, Fiber optic, No).
OnlineSecurity: Whether the customer has online security (Yes, No, No internet service).
DeviceProtection: Whether the customer has device protection (Yes, No, No internet service).
TechSupport: Whether the customer has tech support (Yes, No, No internet service).
StreamingTV: Whether the customer has streaming TV (Yes, No, No internet service).
StreamingMovies: Whether the customer has streaming movies (Yes, No, No internet service).
Contract: Type of contract (Month-to-month, One year, Two year).
PaperlessBilling: Whether the customer has paperless billing (Yes, No).
PaymentMethod: Payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)).
MonthlyCharges: The amount charged to the customer monthly.
TotalCharges: The total amount charged to the customer.
Churn: Whether the customer churned (Yes, No).

Usage:
Open the Jupyter notebooks and Tableau dashboards to explore the data preprocessing, EDA, and visualization steps.
The Tableau workbook (ChurnProject.twb) can be opened with Tableau to view and interact with the visualizations.

Analysis:
The analysis is divided into three main parts:
Data Preprocessing: Handling missing values, encoding categorical variables, and ensuring data quality.
Exploratory Data Analysis (EDA): Understanding the data distribution, identifying patterns, and visualizing relationships.
Visualization: Creating interactive visualizations in Tableau to present the findings.

Results:
Key findings from the analysis include:
Higher churn rates among month-to-month contract customers and fiber optic internet users.
Significant predictors of churn include tenure, monthly charges, contract type, and internet service type.
Strategies to reduce churn include improving contract terms, enhancing service quality, offering personalized retention initiatives, and providing financial incentives.

Recommendations:
Based on the analysis, the following recommendations are made to reduce churn:
Introduce loyalty programs and incentives for long-term contracts.
Improve service quality for high-churn segments.
Develop personalized retention strategies for high-risk customers.
Offer flexible payment options and financial incentives.
Promote additional services to enhance customer value.
