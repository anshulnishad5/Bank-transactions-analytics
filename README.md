# Bank Transactions & Account Holders Analytics

**Bank Transactions & Account Holders Analytics using MySQL and Power BI**

---

## 📌 Project Overview

This project analyzes bank account and transaction data to identify transaction trends, account activity, payment method performance, transaction status, and key business insights.

The project was developed as a **team-based Data Analytics project** using **MySQL and Power BI**.

The main goal was to transform raw banking data into meaningful insights that can support business decision-making and performance monitoring.

---

## 🛠️ Tools & Technologies

- **MySQL** – Data querying, validation, and business analysis
- **Power BI** – Interactive dashboards and data visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Calculated measures and KPI analysis
- **Excel/CSV** – Dataset storage and preparation

---

## 📊 Dataset

The project contains:

- **1,500** account records
- **12,207** transaction records
- Approximately **2 years** of transaction data

The dataset contains information related to:

- Account details
- Transaction details
- Transaction amounts
- Transaction dates
- Transaction status
- Payment methods
- Account activity

> **Note:** The dataset is simulated and created for educational and portfolio purposes.

---

## 🔍 SQL Analysis

MySQL was used to explore, validate, and analyze the banking data and answer business-related questions.

### Key SQL Concepts Used

- SELECT and filtering
- WHERE and HAVING
- GROUP BY
- ORDER BY
- Aggregate functions
- CASE WHEN
- INNER JOIN
- LEFT JOIN
- Subqueries
- CTEs
- Window functions
- Views
- Indexes
- Data validation
- Business analysis

### 📂 SQL Files

- [Database Setup](SQL/01_database_and_tables.sql)
- [Data Validation & Exploratory Data Analysis](SQL/03_exploratory_data_analysis.sql)
- [Business Insights Queries](SQL/04_business_insights_queries.sql)

---

## 📈 Power BI Dashboard

The Power BI dashboard provides an interactive view of banking transaction performance and account activity.

### Key KPIs

- Total Transactions
- Total Transaction Value
- Successful Transactions
- Failed Transactions
- Pending Transactions
- Transaction Success Rate

### Dashboard Analysis

The dashboard analyzes:

- Monthly transaction trends
- Transaction status
- Payment method performance
- Account activity
- Transaction value
- Transaction volume
- Customer/account-level performance
- Transaction success and failure patterns

### 📸 Dashboard Preview

![Bank Transactions Dashboard](Dashboard/Dashboard.png)

### 📁 Power BI File

[Download / View Power BI Dashboard](PowerBI/Bank_project_Dashboard.pbix)

> **Note:** GitHub may not preview `.pbix` files directly in the browser. The Power BI file can be downloaded and opened using Microsoft Power BI Desktop.

---

## 💡 Key Business Insights

The analysis helps identify:

- Trends in transaction volume and transaction value
- Payment methods with higher transaction activity
- Successful, failed, and pending transaction patterns
- Monthly changes in transaction performance
- High-value and high-activity accounts
- Areas that may require further business attention

### 📌 Key Findings

- Analyzed transaction volume and transaction value across approximately two years of data.
- Compared successful, failed, and pending transactions to understand overall transaction performance.
- Evaluated different payment methods based on transaction volume and transaction status.
- Identified monthly transaction trends to understand changes in banking activity.
- Analyzed account-level transaction activity to identify high-value and high-activity accounts.
- Used SQL joins, aggregations, CTEs, subqueries, and window functions to answer business questions.
- Built an interactive Power BI dashboard to present KPIs, trends, and transaction performance in an easy-to-understand format.

---

## 🎯 Business Objective

The primary objective of this project is to analyze banking transaction data and generate actionable insights that can help understand:

1. Transaction performance
2. Payment method usage
3. Transaction success and failure
4. Monthly transaction trends
5. Account-level activity
6. Transaction value and volume
7. Overall banking performance

The analysis combines **SQL-based business analysis** with **Power BI visualization** to present the findings in a clear and interactive format.

---

## 👥 Project Type

**Team Project**

### My Contribution

My contribution focused primarily on:

- SQL data analysis
- Business insight queries
- Data validation
- Exploratory data analysis
- Power BI reporting support
- Dashboard analysis
- Identifying and presenting business insights

---

## 🧠 Skills Demonstrated

### SQL

- Data filtering and aggregation
- GROUP BY and HAVING
- Joins
- CASE statements
- Subqueries
- CTEs
- Window functions
- Views
- Indexes
- Data validation
- Business analysis

### Power BI

- Power Query
- Data transformation
- Data modeling
- DAX measures
- KPI cards
- Interactive visualizations
- Dashboard design
- Business reporting

### Data Analytics

- Data cleaning
- Data validation
- Exploratory Data Analysis
- Business insight generation
- Data visualization
- KPI analysis
- Reporting
- Trend analysis

---

## 📁 Project Structure

```text
bank-transactions-analytics/
│
├── Dataset/
│   ├── accounts.csv
│   └── transactions.csv
│
├── SQL/
│   ├── 01_database_and_tables.sql
│   ├── 03_exploratory_data_analysis.sql
│   └── 04_business_insights_queries.sql
│
├── PowerBI/
│   └── Bank_project_Dashboard.pbix
│
├── Dashboard/
│   └── Dashboard.png
│
├── Documentation/
│   ├── Project_Insights.pdf
│   └── Data_Dictionary.xlsx
│
└── README.md
