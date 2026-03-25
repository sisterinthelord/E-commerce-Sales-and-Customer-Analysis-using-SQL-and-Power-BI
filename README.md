# E-commerce-Sales-and-Customer-Analysis-using-SQL-and-Power-BI
🛍️ E-Commerce Customer & Sales Analysis (Kaggle Dataset)


📘 Project Overview

This project analyzes an e-commerce dataset sourced from Kaggle, focusing on customer behaviour, product performance, and payment trends.

Using SQL for data exploration and Power BI for visualization, the project uncovers key business insights and presents them through an interactive dashboard.


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


📊 Exploratory Data Analysis
Key Metrics
Total Orders: 49
Total Revenue: 1628
Average Payment Value: 33.22
Average Rating: 3.62


👥 Customer Segmentation
Age Group Segmentation

Customers were grouped into:

15–25
26–35
36–45
46+

This segmentation helps identify which age groups contribute most to sales and engagement.

📈 Dashboard Features
KPI summary (Revenue, Orders, Ratings)
Revenue by Brand
Revenue by Gender
Payment Method Distribution
Top Customers by Spend
Highest Rated Brands
Revenue Trend Over Time


📈 Key Metrics
Total Revenue → Sum of all transactions
Total Orders → Number of purchases
Average Payment Value → Average spend per transaction
Average Rating → Customer satisfaction level


🧭 Key Insights
ASUS generated the highest total revenue, indicating strong product demand.
Customers aged 26–35 contributed the largest share of sales, making them a key target segment.
Debit card is the most frequently used payment method, highlighting customer preference for direct payments.
The average rating of 3.62 suggests moderate customer satisfaction, indicating room for improvement.
A small group of customers contributes a significant portion of total revenue, showing the presence of high-value users.
USHA has the highest average rating (4.3), indicating strong customer satisfaction and product quality.
Sales peaked in February, suggesting a potential seasonal or promotional trend.


🧠 Business Recommendations
Increase marketing focus on high-performing brands like ASUS
Develop loyalty programs for top-spending customers
Optimize debit card payment experience for smoother transactions
Improve lower-rated products to enhance customer satisfaction
Promote highly rated brands (e.g., USHA) to boost trust and conversions
Target the 26–35 age group with personalized campaigns
Align promotions with observed sales peaks (e.g., February trends)



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
    └── dashboard.png

    📸 Visuals

<img width="1350" height="750" alt="image" src="https://github.com/user-attachments/assets/dd671a3f-ec94-4adf-88fd-937a0e4757a2" />


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



