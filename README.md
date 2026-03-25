# E-commerce-Sales-and-Customer-Analysis-using-SQL-and-Power-BI
🛍️ E-Commerce Customer & Sales Analysis (Kaggle Dataset)


📘 Project Overview

This project analyzes a structured e-commerce dataset sourced from Kaggle, containing customer transactions, product details, payment behaviour, and ratings.

The goal is to uncover customer purchasing patterns, product performance, and payment insights using SQL for data analysis and Power BI for visualisation, ultimately delivering actionable business insights through an interactive dashboard.


🎯 Objectives
Analyze customer demographics (age, gender) and purchasing behaviour
Evaluate product and brand performance using revenue and ratings
Identify top customers contributing the most revenue
Examine payment method trends and their impact on sales
Build a clean and interactive Power BI dashboard for decision-making

🧩 Dataset Description
| Column        | Description                                              |
| ------------- | -------------------------------------------------------- |
| id_count      | Product/category grouping identifier                     |
| Gender        | Customer gender                                          |
| Age           | Customer age                                             |
| Product_id    | Product identifier                                       |
| Brand         | Product brand                                            |
| Payment_value | Amount paid per transaction                              |
| Max_price     | Maximum listed price                                     |
| Min_price     | Minimum listed price                                     |
| Rating        | Customer rating (1–5 scale)                              |
| Payment_type  | Payment method (e.g., credit card, debit card, UPI, COD) |
| Date          | Transaction date                                         |
| User_id       | Unique customer identifier                               |


🧹 Data Cleaning Steps
Verified dataset contained no missing values
Checked for duplicate records using SQL (GROUP BY + HAVING)
Standardized column naming for SQL compatibility
Ensured correct data types:
Numeric: Payment_value, Rating, Age
Date: Date column
Created Age Group column in Power BI for segmentation


📊 Exploratory Analysis (SQL Queries)

| Analysis                     | Key Insight                                                   |
| ---------------------------- | ------------------------------------------------------------- |
| Total Revenue                | Overall revenue generated from transactions                   |
| Customer Gender Distribution | Balanced participation across genders                         |
| Top Brands by Revenue        | Certain brands significantly outperform others                |
| Average Rating by Brand      | Some brands consistently receive higher customer satisfaction |
| Payment Type Distribution    | Card and digital payments dominate transactions               |
| Top Customers by Spend       | A small number of users contribute a large share of revenue   |
| Revenue Over Time            | Identifies spending trends across dates                       |




👥 Customer Segmentation
Age Group Segmentation

Customers were grouped into:

15–25
26–35
36–45
46+

This segmentation helps identify which age groups contribute most to sales and engagement.


📈 Key Metrics
Total Revenue → Sum of all transactions
Total Orders → Number of purchases
Average Payment Value → Average spend per transaction
Average Rating → Customer satisfaction level


🧭 Key Findings
A small number of customers account for a disproportionately high share of total revenue
Certain brands dominate both sales and customer ratings
Customers within specific age groups contribute more significantly to revenue
Digital payment methods (credit/debit) are the most commonly used
Average rating indicates generally positive customer satisfaction



🧠 Business Recommendations
Target high-value customers with loyalty and retention strategies
Promote top-performing brands through marketing campaigns
Focus on preferred payment methods to streamline checkout experience
Personalize marketing based on age group behaviour
Monitor lower-rated products to improve customer satisfaction



💻 Tools Used
SQL (SQL Server / SSMS) → Data exploration and analysis
Power BI → Dashboard creation and visualisation
DAX → Calculated columns and measures (e.g., Age Group, KPIs)

📂 Project Structure
Ecommerce-Analysis/
│
├── data/
│   └── ecommerce_dataset.csv
│
├── sql/
│   ├── data_exploration.sql
│   ├── analysis_queries.sql
│
├── powerbi/
│   └── ecommerce_dashboard.pbix
│
├── README.md
└── screenshots/
    ├── dashboard_overview.png
    ├── top_brands.png
    ├── payment_analysis.png
    └── customer_insights.png


    📸 Visuals

(Insert your Power BI screenshots here)

KPI Summary (Revenue, Orders, Ratings)
Top Brands by Revenue
Customer Gender & Age Distribution
Payment Type Breakdown
Revenue Trend Over Time



🚀 Future Work
Implement advanced customer segmentation (RFM analysis)
Perform predictive analysis on customer spending
Automate data pipeline using Python (pandas, SQLAlchemy)
Build a more interactive dashboard with filters and drill-through
Integrate larger datasets for deeper insights



