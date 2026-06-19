# 🏦 Comprehensive Banking Database

A synthetic banking dataset containing customer demographics, account information, transactions, loans, credit card details, customer feedback, and anomaly indicators. This dataset is useful for data analysis, machine learning, fraud detection, customer segmentation, and financial analytics projects.

## 📊 Dataset Overview

The dataset contains **5,000 records** and **26 features**, covering multiple banking domains:

* Customer Information
* Account Details
* Transaction Records
* Loan Information
* Credit Card Data
* Customer Feedback
* Anomaly Detection Labels

## 📁 Dataset Structure

| Column              | Description                         |
| ------------------- | ----------------------------------- |
| Customer ID         | Unique customer identifier          |
| First Name          | Customer first name                 |
| Last Name           | Customer last name                  |
| Age                 | Customer age                        |
| Gender              | Customer gender                     |
| City                | Customer city                       |
| Email               | Customer email address              |
| Account Type        | Savings/Current account type        |
| Account Balance     | Current account balance             |
| TransactionID       | Unique transaction identifier       |
| Transaction Type    | Deposit, Withdrawal, Transfer, etc. |
| Transaction Amount  | Amount involved in transaction      |
| Loan Issue Date     | Date loan was issued                |
| Loan ID             | Unique loan identifier              |
| Loan Amount         | Loan principal amount               |
| Loan Type           | Type of loan                        |
| Interest Rate       | Loan interest rate                  |
| Loan Term           | Loan duration                       |
| Loan Status         | Active, Closed, Defaulted, etc.     |
| Card Type           | Credit/Debit card type              |
| Credit Limit        | Card credit limit                   |
| Minimum Payment Due | Minimum card payment amount         |
| Rewards Points      | Customer reward points              |
| Feedback Type       | Complaint, Praise, Suggestion, etc. |
| Resolution Status   | Feedback resolution status          |
| Anomaly             | Binary anomaly indicator (0/1)      |

## 🎯 Potential Use Cases

### 1. Customer Segmentation

* Age-based segmentation
* Geographic analysis
* Account type analysis
* Customer value categorization

### 2. Transaction Analytics

* Spending pattern analysis
* Transaction volume trends
* Deposit vs Withdrawal analysis
* Customer transaction behavior

### 3. Loan Risk Assessment

* Loan approval analysis
* Default prediction
* Interest rate impact studies
* Loan portfolio management

### 4. Fraud & Anomaly Detection

* Detect suspicious transactions
* Identify unusual account activities
* Build anomaly detection models
* Financial risk monitoring

### 5. Customer Experience Analysis

* Feedback classification
* Resolution effectiveness tracking
* Customer satisfaction insights
* Service improvement recommendations

## 📈 Example Analysis Questions

* Which cities have the highest account balances?
* What transaction types are most common?
* How does age impact loan amounts?
* Which loan types have the highest default rates?
* Are anomalies associated with specific transaction patterns?
* What factors influence customer rewards points?

## 🛠️ Technologies Suitable for Analysis

* Python

  * Pandas
  * NumPy
  * Scikit-Learn
  * Matplotlib
  * Seaborn
* SQL
* Power BI
* Tableau
* Apache Spark

## 🚀 Getting Started

### Load Dataset Using Python

```python
import pandas as pd

df = pd.read_csv("Comprehensive_Banking_Database.csv")

print(df.head())
print(df.shape)
print(df.info())
```

### Basic Statistics

```python
print(df.describe())
```

### Check Missing Values

```python
print(df.isnull().sum())
```

## 📊 Machine Learning Applications

* Customer Churn Prediction
* Fraud Detection
* Anomaly Detection
* Loan Default Prediction
* Customer Lifetime Value Prediction
* Customer Segmentation (Clustering)
* Credit Risk Analysis

## 📌 Dataset Characteristics

* Records: **5,000**
* Features: **26**
* Mixed Data Types:

  * Numerical
  * Categorical
  * Date Fields
* Suitable for:

  * EDA
  * Visualization
  * Machine Learning
  * Data Engineering Projects

## 📜 License

This dataset is intended for educational, research, and demonstration purposes. Ensure compliance with your organization's data governance and privacy policies before production use.

## 🤝 Contributions

Contributions, improvements, and feature engineering suggestions are welcome. Feel free to fork the repository and submit pull requests.

---

⭐ If you find this dataset useful, consider giving the repository a star!
