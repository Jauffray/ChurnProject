
**Telco Customer Churn Analysis Project**
<br /><br />
**Overview:**<br />
This project analyzes customer churn at a Telco company to identify the factors that influence churn and provide actionable insights to reduce it. The analysis includes data preprocessing and exploratory data analysis (EDA) to uncover patterns and trends in customer behavior. The results are visualized using Tableau for better interpretation and presentation.
<br /><br />
**Link the Tableau dashboards:** https://public.tableau.com/app/profile/jauffray.bruneton/viz/ChurnProject_17165914665310/ChurnStory?publish=yes

Please check the **"Analysis of Customer Churn in Telco Company.pdf"** for a nicely presented report of the project.

Please check the **"Churn Notebook.ipynb"** for a preview of the Python work I made using Pandas on Jupyter Notebook.
<br /><br /><br /><br /><br />


**Table of Contents:**<br />
Introduction<br />
Dataset<br />
Usage<br />
Analysis<br />
Results<br />
Recommendations<br />

**Introduction:**<br />
Customer churn is a critical issue for telecom companies as it directly impacts revenue and growth. This project aims to understand the factors driving customer churn and suggest strategies to improve customer retention.<br />

**Dataset:**<br />
The dataset used in this analysis contains information on 7,043 customers, with 21 columns capturing various attributes, including demographic information, service subscriptions, payment details, and churn status.<br />

**Key columns:**<br />
customerID: Unique identifier for each customer.<br />
gender: Gender of the customer (Male, Female).<br />
SeniorCitizen: Indicates if the customer is a senior citizen (1) or not (0).<br />
Partner: Whether the customer has a partner (Yes, No).<br />
Dependents: Whether the customer has dependents (Yes, No).<br />
tenure: Number of months the customer has stayed with the company.<br />
PhoneService: Whether the customer has phone service (Yes, No).<br />
MultipleLines: Whether the customer has multiple lines (No, Yes, No phone service).<br />
InternetService: Type of internet service (DSL, Fiber optic, No).<br />
OnlineSecurity: Whether the customer has online security (Yes, No, No internet service).<br />
DeviceProtection: Whether the customer has device protection (Yes, No, No internet service).<br />
TechSupport: Whether the customer has tech support (Yes, No, No internet service).<br />
StreamingTV: Whether the customer has streaming TV (Yes, No, No internet service).<br />
StreamingMovies: Whether the customer has streaming movies (Yes, No, No internet service).<br />
Contract: Type of contract (Month-to-month, One year, Two year).<br />
PaperlessBilling: Whether the customer has paperless billing (Yes, No).<br />
PaymentMethod: Payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)).<br />
MonthlyCharges: The amount charged to the customer monthly.<br />
TotalCharges: The total amount charged to the customer.<br />
Churn: Whether the customer churned (Yes, No).<br />

**Usage:**<br />
Open the Jupyter notebooks and Tableau dashboards to explore the data preprocessing, EDA, and visualization steps.<br />
The Tableau workbook (ChurnProject.twbx) can be opened with Tableau to view and interact with the visualizations.<br />

**Analysis:**<br />
The analysis is divided into three main parts:<br />
Data Preprocessing: Handling missing values, encoding categorical variables, and ensuring data quality.<br />
Exploratory Data Analysis (EDA): Understanding the data distribution, identifying patterns, and visualizing relationships.<br />
Visualization: Creating interactive visualizations in Tableau to present the findings.<br />

**Results:**<br />
Key findings from the analysis include:
Higher churn rates among month-to-month contract customers and fiber optic internet users.<br />
Significant predictors of churn include tenure, monthly charges, contract type, and internet service type.<br />
Strategies to reduce churn include improving contract terms, enhancing service quality, offering personalized retention initiatives, and providing financial incentives.<br />

**Recommendations:**<br />
Based on the analysis, the following recommendations are made to reduce churn:<br />
Introduce loyalty programs and incentives for long-term contracts.<br />
Improve service quality for high-churn segments.<br />
Develop personalized retention strategies for high-risk customers.<br />
Offer flexible payment options and financial incentives.<br />
Promote additional services to enhance customer value.<br />
