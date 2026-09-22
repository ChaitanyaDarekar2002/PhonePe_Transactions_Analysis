# 📱 PhonePe Transactions Analysis & Power BI Dashboard

## 📊 Project Overview

An end-to-end **PhonePe Transactions Analysis** project using **Excel, Python, and Power BI** to analyze transactions, payment performance, services, and monthly trends.

**Workflow:**  
Excel Dataset → Python Cleaning & Analysis → Power BI Dashboard

## 🛠️ Tools Used

- Microsoft Excel
- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Power BI
- DAX
- Git & GitHub

## 📂 Dataset

The Excel dataset contains 6 sheets:

- `All_Users`
- `All_Transactions`
- `Recharge_Bills`
- `Money_Transfer`
- `Loans`
- `Insurance`

## 🐍 Python Analysis

Python was used for:

- Data cleaning
- Missing value analysis
- Duplicate checking
- Data type conversion
- Transaction analysis
- Payment status analysis
- Failed payment reason analysis
- Monthly trend analysis
- Data visualization

## 📊 Power BI Dashboards

The Power BI report contains **5 interactive dashboards**.

### 🏠 1. Home Dashboard

Provides an overall view of:

- Total Amount
- Total Transactions
- Successful Transactions
- Failed Transactions
- Services vs Amount
- Failed Payment Reasons
- Monthly Transaction Trends

**Dashboard Preview:**

![Home Dashboard](images/home_dashboard.png)

<br>

### 🛡️ 2. Insurance Dashboard

Analyzes:

- Insurance Amount
- Payment Status
- Failed Payment Reasons
- Insurance Categories
- Monthly Premium Trends

**Dashboard Preview:**

![Insurance Dashboard](images/insurance_dashboard.png)

<br>

### 💰 3. Loans Dashboard

Analyzes:

- Loan Amount
- Loan Transactions
- Payment Status
- Loan Categories
- Failed Payment Reasons
- Monthly Trends

**Dashboard Preview:**

![Loans Dashboard](images/loans_dashboard.png)

<br>

### 💸 4. Money Transfer Dashboard

Analyzes:

- Transfer Amount
- Total Transactions
- Payment Status
- Transfer Types
- Failed Payment Reasons
- Monthly Trends

**Dashboard Preview:**

![Money Transfer Dashboard](images/money_transfer_dashboard.png)

<br>

### 📱 5. Recharge & Bills Dashboard

Analyzes:

- Recharge & Bill Amount
- Total Transactions
- Payment Status
- Recharge Categories
- Failed Payment Reasons
- Monthly Trends

**Dashboard Preview:**

![Recharge & Bills Dashboard](images/recharge_bills_dashboard.png)

## 📌 Key Insights

- Analyzed overall PhonePe transaction performance.
- Compared different PhonePe services.
- Identified successful and failed payments.
- Analyzed major payment failure reasons such as Wrong PIN, Server Error, and Insufficient Amount.
- Studied monthly transaction and amount trends.
- Created separate dashboards for Insurance, Loans, Money Transfer, and Recharge & Bills.

## 📁 Project Structure

```text
PhonePe-Transactions-Analysis/
│
├── PhonePe_Transactions.xlsx
├── PhonePe_Transactions_Analysis.ipynb
├── PhonePe_Dashboard.pbix
├── README.md
│
└── images/
    ├── home_dashboard.png
    ├── insurance_dashboard.png
    ├── loans_dashboard.png
    ├── money_transfer_dashboard.png
    └── recharge_bills_dashboard.png
