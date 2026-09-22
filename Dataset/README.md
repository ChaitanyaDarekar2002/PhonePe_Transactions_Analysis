# 📱 PhonePe Transactions Analysis

## 📊 Project Overview

This project analyzes a large **PhonePe transaction dataset** using **Python and Microsoft Excel** to understand transaction behavior, payment performance, user activity, and different financial services.

The project follows an end-to-end data analytics workflow:

**Excel Dataset → Python Data Cleaning → Exploratory Data Analysis → Visualization → Insights**

The dataset contains user information and transaction data across different PhonePe services such as money transfers, recharge & bill payments, loans, and insurance.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze overall transaction activity
- Understand user transaction behavior
- Analyze successful and failed payments
- Identify major payment failure reasons
- Analyze transaction amounts
- Study different PhonePe services
- Analyze recharge and bill payments
- Analyze money transfer transactions
- Analyze loan transactions
- Analyze insurance transactions
- Identify trends and patterns in transaction data
- Generate meaningful business insights using Python

---

## 📂 Dataset

The dataset is provided in an Excel workbook:

**`PhonePe_Transactions.xlsx`**

The workbook contains 6 different sheets.

### 1. All_Users

Contains information about PhonePe users.

| Column | Description |
|---|---|
| User_ID | Unique user identifier |
| Name | User name |
| Age | User age |
| Join_Date | Date when the user joined |

---

### 2. All_Transactions

Contains overall transaction-level information.

| Column | Description |
|---|---|
| Transaction_ID | Unique transaction identifier |
| Amount | Transaction amount |
| User_ID | User identifier |
| Service | PhonePe service used |
| Service Type | Type of service |
| Payment_Status | Payment status |
| Reason | Reason for payment status |
| Date | Transaction date |

---

### 3. Recharge_Bills

Contains recharge and bill payment transactions.

| Column | Description |
|---|---|
| Transaction_ID | Unique transaction identifier |
| User_ID | User identifier |
| Recharge_Type | Type of recharge/bill |
| Amount | Transaction amount |
| Date | Transaction date |
| Payment_Status | Payment status |
| Reason | Reason for payment status |

---

### 4. Money_Transfer

Contains money transfer transactions.

| Column | Description |
|---|---|
| Transaction_ID | Unique transaction identifier |
| User_ID | User identifier |
| Transfer_Type | Type of money transfer |
| Amount | Transfer amount |
| Date | Transaction date |
| Payment_Status | Payment status |
| Reason | Reason for payment status |

---

### 5. Loans

Contains loan-related transaction information.

| Column | Description |
|---|---|
| Transaction_ID | Unique transaction identifier |
| User_ID | User identifier |
| Loan_Type | Type of loan |
| Loan_Amount | Loan amount |
| Date | Transaction date |
| Payment_Status | Payment status |
| Reason | Reason for payment status |

---

### 6. Insurance

Contains insurance-related transaction information.

| Column | Description |
|---|---|
| Transaction_ID | Unique transaction identifier |
| User_ID | User identifier |
| Insurance_Type | Type of insurance |
| Premium | Insurance premium |
| Date | Transaction date |
| Payment_Status | Payment status |
| Reason | Reason for payment status |

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook**
- **Microsoft Excel**
- **Git**
- **GitHub**

---

## 🔄 Project Workflow

### Step 1: Dataset Collection

The PhonePe transaction dataset was provided in an Excel workbook containing multiple sheets.

### Step 2: Data Loading

The Excel workbook was imported into Python using Pandas.

```python
import pandas as pd

file_path = "PhonePe_Transactions.xlsx"

users = pd.read_excel(file_path, sheet_name="All_Users")
transactions = pd.read_excel(file_path, sheet_name="All_Transactions")
recharge = pd.read_excel(file_path, sheet_name="Recharge_Bills")
money_transfer = pd.read_excel(file_path, sheet_name="Money_Transfer")
loans = pd.read_excel(file_path, sheet_name="Loans")
insurance = pd.read_excel(file_path, sheet_name="Insurance")
