## 📊 Blinkit Sales Analysis Dashboard

#### 📝 Project Overview
This project analyzes Blinkit grocery sales data to derive insights into product performance, outlet distribution, and customer purchasing behavior.
The analysis was performed using Python (Pandas, Matplotlib) for data cleaning & exploration, and the results were visualized through an interactive Power BI dashboard.
The goal is to help stakeholders understand sales trends, outlet performance, product demand, and ratings distribution to make better business decisions.

## 📂 Dataset
- Source: BlinkIT Grocery Data (Excel file, 8,523 records, 13 columns)
#### Key Columns:
- Item Identifier – Unique product code
- Item Type – Category of product (e.g., Frozen Foods, Dairy, Soft Drinks)
- Item Fat Content – Product type (Low Fat, Regular)
- Outlet Type – Store type (Supermarket Type1/2/3, Grocery Store)
- Outlet Location Type – Tier-based location (Tier 1, 2, 3)
- Outlet Size – Small, Medium, High
- Sales – Sales value of the product
- Rating – Customer rating for the product

## ⚙️ Tools & Technologies
- Python: Data Cleaning & Analysis (pandas, numpy, matplotlib)
- Excel: Raw dataset & pre-analysis
- Power BI: Interactive dashboard design & KPI visualization

## 🔑 Key Business KPIs
- Total Sales – Overall revenue generated
- Average Sales per Outlet
- Sales by Outlet Type & Location
- Sales by Product Type & Fat Content
- Top Performing Products & Categories
- Customer Ratings Analysis

## 📊 Visualizations in Power BI Dashboard
- Total Sales Overview
- Sales by Outlet Size & Location
- Sales by Product Type & Fat Content
- Year-wise Sales Trends
- Top 10 Products by Sales
- Ratings Distribution

## 🛠 Steps Performed
1. Data Cleaning (Excel & Python)
    - Standardized missing values in emp_title and emp_length
    - Converted categorical encodings (loan status → good/bad loans)
    - Ensured datetime fields (issue_date, last_payment_date) were consistent
2. Exploratory Data Analysis
    - Python EDA for distributions, correlations, and outliers
    - SQL queries for aggregations (defaults per grade, purpose, state)
3. Dashboarding
    - Designed KPIs, trend charts, and categorical breakdowns in Power BI & Tableau

## 🚀 How to View the Project
- Open the Power BI Dashboard:
[View Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMDg1N2E4ZDEtNzZjMi00ZTQyLWFmMDEtZTdhYWVmYmUzODU5IiwidCI6ImVkNGI1YWIzLWM0MzctNGNiMi05NzczLTYzZDdlMTc0OWVhNyJ9)
- Explore the Python Notebook:
    - Open cmd and write the command:
        - jupyter notebook Blinkit_Analysis.ipynb

## 📌 Key Insights
- Tier 3 outlets contributed the highest revenue.
- Regular fat items showed higher sales compared to low-fat.
- Supermarket Type1 generated the majority of overall sales.
- Customer ratings were mostly favorable (average ~4.5/5).

## 📸 Dashboard Preview
![Blinkit Dashboard](./assets/Snapshot%20of%20Dashboard.png)