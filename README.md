**Customer Shopping Behavior Analysis**

An end-to-end Data Analytics project using Python, PostgreSQL, SQL, and Power BI to analyze customer purchasing behavior and generate actionable business insights.

**Project Overview**

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The goal of this analysis is to identify customer trends, purchasing patterns, subscription behavior, and revenue-driving factors that can help businesses improve customer engagement and marketing strategies.

The project covers:

-> Data Cleaning & Preparation using Python
-> Exploratory Data Analysis (EDA)
-> SQL-based Business Analysis
-> Interactive Power BI Dashboard
-> Business Insights & Recommendations

**Business Problem**

A retail company wanted to better understand customer shopping behavior to improve:

-> Sales performance
-> Customer retention
-> Product positioning
-> Marketing effectiveness
-> Customer loyalty

This project helps answer:

“How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?”

**Repository Structure**

Customer-Shopping-Behavior-Analysis/
│
├── Customer_Behavior_Dashboard.pbix
├── Customer_SQL_Queries.sql
├── Customer_Shopping_Behavior_Analysis.pdf
├── Customer-Shopping-Behavior-Analysis.pptx
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_shopping_behavior.csv
├── Business_Problem_Document.pdf
├── README.md
└── LICENSE

**Dataset Information**

-> Total Records: 3,900
-> Total Columns: 18
-> Missing Values: 37 values in the Review Rating column

**Key Features**

-> Customer demographics
-> Product categories
-> Purchase amount
-> Subscription status
-> Shipping type
-> Discounts and promo usage
-> Review ratings
-> Purchase frequency

**Tools & Technologies Used**

| Tool                 | Purpose                    |
| -------------------- | -------------------------- |
| Python               | Data cleaning and analysis |
| Pandas & NumPy       | Data processing            |
| Matplotlib & Seaborn | Visualization              |
| PostgreSQL           | SQL analysis               |
| Power BI             | Dashboard creation         |
| Jupyter Notebook     | Development environment    |
| Gamma                | Presentation creation      |

**Project Workflow**

1. Data Preparation using Python
-> Loaded dataset using pandas
-> Cleaned and transformed data
-> Handled missing values
-> Standardized column names
-> Created new features like:
       -> age_group
       -> purchase_frequency_days

2. Exploratory Data Analysis (EDA)
Performed analysis to identify:
-> Customer spending behavior
-> Revenue trends
-> Purchase patterns
-> Product performance
-> Customer segments

3. SQL Business Analysis
Used PostgreSQL to answer business questions such as:
-> Revenue by gender
-> High-spending discount users
-> Top-rated products
-> Subscription analysis
-> Revenue by age group
-> Customer segmentation
-> Shipping type comparison

4. Power BI Dashboard
Created an interactive dashboard with:
-> KPI cards
-> Revenue analysis
-> Sales by category
-> Customer segmentation
-> Subscription insights
-> Dynamic slicers and filters

**Key Insights**
-> Female customers generated slightly higher revenue
-> Express shipping users spent more per transaction
-> Subscribers showed higher loyalty and repeat purchases
-> Loyal customers formed the largest customer segment
-> Some products were highly dependent on discounts

**Business Recommendations**
-> Introduce stronger loyalty programs
-> Promote subscription benefits
-> Focus marketing on high-value customers
-> Highlight top-rated products in campaigns
-> Optimize discount strategies for profitability

**How to Run the Project**
Clone Repository
git clone https://github.com/your-username/Customer-Shopping-Behavior-Analysis.git

Install Required Libraries
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2

Run Jupyter Notebook
jupyter notebook

Open Power BI Dashboard

Open:
Customer_Behavior_Dashboard.pbix

**Project Deliverables**
-> Python notebook for EDA and preprocessing
-> SQL queries for business analysis
-> Power BI dashboard
-> Project report
-> Business presentation

**Future Improvements**
-> Deploy dashboard online
-> Add machine learning prediction models
-> Build automated ETL pipeline
-> Add real-time analytics support

**Conclusion**

This project demonstrates an end-to-end data analytics workflow using Python, SQL, and Power BI. It highlights how customer shopping data can be transformed into meaningful business insights that support strategic decision-making.
