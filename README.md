# 📘 README — Personal Finance Dashboard (Power BI)
🧭 Overview

This Power BI dashboard visualizes personal finance data including income, expenses, savings, debt, credit scores, and loan behaviors across different demographic segments. It is designed to provide high-level insights for financial analysts, banking executives, or individual users exploring financial wellness trends.

🧱 Dashboard Structure
🟩 Page 1: Income, Spending & Savings Snapshot

Objective: Show overall financial health by visualizing income, spending, and credit behavior across users.

Key Features:

📊 KPI Cards: Average monthly income, expenses, savings, and credit score

📉 Line/Column Chart: Income vs. Expenses trend (by month and quarter)

🏫 Stacked Column: Monthly expenses by occupation and education level

🥧 Pie Chart: Balanced vs. Efficient Savers

💳 Donut Chart: Credit score by employment status

🔄 Slicers: Gender, Region, Age Group (synced across pages)

🟦 Page 2: Debt & Loan Insights

Objective: Analyze users’ debt load, loan types, and risk indicators.

Key Features:

💳 KPI Cards: Average loan amount, average EMI, average debt-to-income ratio, and % of users with loans

📊 Column Charts:

Loan amounts by type

DTI buckets

📚 Stacked Column: Loan holders by education level

🗺️ Matrix Table: Avg EMI by region and employment status

🍩 Donut Chart: Loan type distribution

📈 Line Chart: Loan interest rate by year

Data Fixes Implemented:

Dynamic slicer syncing across pages

Trimmed and cleaned "Has_Loan" field for accurate measures

💾 Data Source

synthetic_personal_finance_dataset.csv

Includes columns: income, expenses, savings, credit_score, loan_amount, loan_type, monthly_emi, debt_to_income_ratio, demographics, etc.

🎯 Skills Demonstrated

DAX Measures & Calculated Columns

Visual Design Consistency

Slicer Syncing & Cross-page Filtering

Data Cleaning & Logic Debugging

Storytelling with Financial Data
