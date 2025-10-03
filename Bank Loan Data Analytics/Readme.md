## 🏦 Bank Loan Data Analysis

#### 📝 Project Overview
This project analyzes loan application and repayment data to evaluate loan performance, borrower risk profiles, and default trends.
The analysis was performed using SQL, Python, Excel, Power BI, and Tableau to create interactive dashboards for financial stakeholders.
The goal is to identify key risk factors in lending and generate insights to improve loan approval, monitoring, and recovery strategies.

## 📂 Dataset
- Source: Bank Loan Data (38,576 records, 25 columns)
#### Key Columns:
- loan_status – Loan outcome (Fully Paid, Charged Off, Current, etc.)
- Good vs Bad Loan – Derived indicator for default analysis
- loan_amount – Amount requested by borrower
- int_rate – Interest rate applied
- annual_income – Borrower’s income
- dti – Debt-to-Income ratio
- grade / sub_grade – Credit rating tiers
- home_ownership, emp_length, purpose – Borrower demographics
- total_payment – Final amount repaid

## ⚙️ Tools & Technologies
- Excel – Data exploration & preprocessing
- SQL – Querying & aggregations for loan status insights
- Python – Exploratory Data Analysis (pandas, matplotlib, seaborn)
- Power BI & Tableau – Interactive dashboards for visualization

## 🔑 Key Business KPIs
- Total Applications – Number of loan applications received
- Good Loan vs Bad Loan % – Loan performance segmentation
- Total Funded Amount – Value of loans issued
- Total Amount Received – Payments collected from borrowers
- Average Interest Rate & DTI – Risk assessment indicators
- Loan Status Breakdown – Fully Paid, Current, Charged Off

## 📊 Visualizations in Dashboards
- Loan Applications by Status, Grade, Purpose, and State
- Good vs Bad Loan Ratio
- Income vs Loan Amount Distribution
- Interest Rate & DTI Impact on Defaults
- Trend Analysis (Monthly/Quarterly Loan Issuance & Payments)

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
- Open the Tableau Dashboard:
   [View Dashboard](https://public.tableau.com/app/profile/krishna.mittal6200/viz/BankLoanDataAnalysis_17592567907460/SUMMARY#1)
- Explore the Python Notebook:
   - Open cmd and write the command:
      - jupyter notebook Bank_loan_data_analysis.ipynb

## 📌 Key Insights
- ~85% loans were “Good Loans”, while ~15% were defaults/charged-off.
- Higher default rates among borrowers with low income + high DTI.
- Grade C & D loans showed more risk compared to A/B grades.
- Home ownership and employment length played a role in repayment likelihood.
- Debt-to-Income ratio > 20% strongly correlated with defaults.

## 📸 Dashboard Preview
### PowerBI Dashboard
## 📄 Summary Dashboard
![Bank Loan Summary Dashboard](./assets/Snapshot%20of%20Summary%20dashboard%20-%20PowerBI.png)
<details>
  <summary>📂 Click to view Overview & Details Dashboards</summary>

### 📋 Overview Dashboard
Shows **customer demographics, loan purposes, and distribution trends**.  

![Bank Loan Overview Dashboard](./assets/Snapshot%20of%20Overview%20Dashboard%20-%20PowerBI.png)

---

### 📑 Details Dashboard
Provides **granular insights into loan status, grade, subgrade, and repayment performance**.  

![Bank Loan Details Dashboard](./assets/Snapshot%20of%20Details%20Dashboard%20-%20PowerBI.png)

</details>

### Tableau Dashboard
## 📄 Summary Dashboard
![Bank Loan Summary Dashboard](./assets/Snapshot%20of%20Summary%20dashboard%20-%20Tableau.png)
<details>
  <summary>📂 Click to view Overview & Details Dashboards</summary>

### 📋 Overview Dashboard
Shows **customer demographics, loan purposes, and distribution trends**.  

![Bank Loan Overview Dashboard](./assets/Snapshot%20of%20Overview%20Dashboard%20-%20Tableau.png)

---

### 📑 Details Dashboard
Provides **granular insights into loan status, grade, subgrade, and repayment performance**.  

![Bank Loan Details Dashboard](./assets/Snapshot%20of%20Details%20Dashboard%20-%20Tableau.png)

</details>