# Goldman Sachs Financial Risk Analysis using Python

## Project Overview

This project analyzes banking transaction data using Python to understand customer behavior, identify financial risks, perform customer segmentation, validate business assumptions through statistical testing, and generate actionable business insights.

The project simulates a real-world financial analytics use case where data analysts support banking institutions by transforming raw transaction data into meaningful business intelligence.

---

## Business Problem

Financial institutions process thousands of transactions every day.

Understanding customer transaction behavior is critical for:

- Identifying financial risks
- Monitoring customer activity
- Detecting abnormal transaction patterns
- Improving customer segmentation
- Supporting data-driven decision making

This project answers key business questions by combining data preparation, statistical analysis, and visualization techniques.

---

## Objectives

- Clean and prepare banking transaction data
- Analyze customer transaction behavior
- Build customer activity profiles
- Identify potential financial risks
- Perform exploratory data analysis
- Validate business assumptions using hypothesis testing
- Generate actionable business recommendations

---

## Dataset

The dataset contains **800 banking transactions** with customer, account, and transaction information including:

- Customer ID
- Account ID
- Account Type
- Transaction Type
- Transaction Amount
- Account Balance
- Credit Rating
- Risk Score
- Transaction Date
- Region
- Product
- Relationship Manager

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

---

## Python Concepts Used

- Data Cleaning
- Data Wrangling
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Customer Segmentation
- Statistical Analysis
- Hypothesis Testing
- Correlation Analysis
- Data Visualization

---

# Project Workflow

## 1. Data Cleaning & Preparation

- Date formatting
- Negative value correction
- Risk score validation
- Missing value verification
- Feature engineering

---

## 2. Descriptive Transaction Analysis

- Monthly transaction summaries
- Yearly transaction summaries
- Credit vs Debit analysis
- Dormant account identification
- Top and bottom performing accounts

---

## 3. Customer Profile Building

Customer segmentation based on:

- Transaction Frequency
- Average Account Balance
- Transaction Volume
- Net Inflow

Customer profiles created:

- High Activity Customers
- Medium Activity Customers
- Low Activity Customers
- High Net Inflow Accounts
- High Frequency Low Balance Accounts

---

## 4. Financial Risk Analysis

- Overdraft detection
- Large withdrawal analysis
- Balance volatility analysis
- IQR anomaly detection
- Z-Score analysis
- Suspicious customer identification

---

## 5. Exploratory Data Analysis

Created multiple business visualizations including:

- Account Type Distribution
- Transaction Type Distribution
- Transaction Amount Distribution
- Monthly Transaction Trends
- Average Balance by Account Type
- Risk Score Distribution
- Credit Rating vs Risk Score
- Correlation Heatmap
- Monthly Credit vs Debit Trend
- Regional Transaction Analysis

---

## 6. Hypothesis Testing

Performed statistical validation using:

- Levene's Test
- Independent Samples t-Test
- Mann–Whitney U Test

Objective:

Determine whether customers with higher transaction volumes maintain significantly higher average account balances.

---

# Key Findings

- Successfully cleaned and prepared the banking dataset for analysis.
- Identified **164 dormant accounts** based on transaction inactivity.
- Corrected **24 negative transaction amounts** and **35 invalid risk scores**.
- Detected **16 overdraft transactions** during data preparation.
- Debit transactions consistently exceeded credit transactions throughout the analysis period.
- Customer financial risk was influenced by multiple behavioral factors rather than any single financial metric.
- Statistical testing found no significant evidence that high transaction volume customers maintain higher account balances.

---

# Business Recommendations

- Monitor customers with high balance volatility more closely.
- Re-engage dormant account holders through targeted campaigns.
- Continue monitoring repeated overdraft accounts.
- Use multiple financial indicators instead of relying on a single metric for customer evaluation.
- Implement periodic anomaly detection as part of financial risk monitoring.

---

# Skills Demonstrated

- Python Programming
- Pandas
- NumPy
- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Analysis
- Hypothesis Testing
- Customer Segmentation
- Financial Risk Analytics
- Business Intelligence
- Analytical Reporting

---

## Repository Structure

```text
financial-risk-analysis/
│
├── data/
│   ├── goldman_sachs.csv
│   └── goldman_sachs_cleaned.csv
│
├── docs/
│   ├── Analytical_Criterias_followed.ipynb
│   ├── Financial Risk Analysis Summary Report.pdf
│   ├── Problem Statement.pdf
│   └── Video Link.txt
│
├── images/
│   ├── Transaction_amount_distribution.png
│   ├── correlation heatmap.png
│   ├── credit_rating_vs_risk_score.png
│   ├── customer_profile_building.png
│   ├── hypothesis_testing.png
│   ├── monthly_credit_vs_debit_transactions.png
│   └── risk_score_distribution_by_account_type.png
│
├── solution/
│   ├── Task1_Cleaning.ipynb
│   ├── Task2_Descriptive_Transactional_Analysis.ipynb
│   ├── Task3_Customer_Profile_Building.ipynb
│   ├── Task4_Financial_Risk_Identification.ipynb
│   ├── Task5_Exploratory_Data_Analysis.ipynb
│   └── Task6_Hypothesis_Testing.ipynb
│
├── .gitignore
├── README.md
└── requirements.txt
```

---

# Project Outcome

This project demonstrates how Python can be applied to solve real-world banking analytics problems through data preparation, exploratory analysis, customer segmentation, statistical validation, and business reporting.

The project showcases an end-to-end analytics workflow commonly used by financial institutions to support customer profiling, risk monitoring, and strategic decision-making.

---

## Author

**Ananthakrishna Nair**
