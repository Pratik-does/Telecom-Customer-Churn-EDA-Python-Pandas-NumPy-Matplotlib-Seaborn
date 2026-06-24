# Telecom Customer Churn Analysis | Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge\&logo=numpy\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![EDA](https://img.shields.io/badge/Analysis-EDA-success?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio_Project-black?style=for-the-badge\&logo=github)

---

## Business Problem

Customer churn is one of the most significant challenges faced by telecom companies. Losing customers directly impacts recurring revenue, customer lifetime value, and profitability.

This project analyzes telecom customer behavior to identify the major factors contributing to customer attrition and provides data-driven recommendations that can improve retention and reduce churn.

---

## Project Overview

This end-to-end Exploratory Data Analysis (EDA) project investigates churn patterns across **7,043 telecom customers** using Python.

The analysis focuses on:

* Customer demographics
* Contract types
* Service subscriptions
* Billing behavior
* Customer tenure
* Revenue-related metrics
* Churn prediction indicators

The goal is to uncover actionable business insights that can help telecom companies improve customer retention strategies.

---

## Project Objectives

* Analyze overall churn behavior
* Identify key churn drivers
* Segment customers based on churn risk
* Understand the impact of contracts and tenure
* Evaluate service usage patterns
* Examine revenue-related trends
* Generate business recommendations backed by data

---

## Tech Stack

| Category             | Technology                     |
| -------------------- | ------------------------------ |
| Programming Language | Python                         |
| Data Manipulation    | Pandas, NumPy                  |
| Data Visualization   | Matplotlib, Seaborn            |
| Environment          | Jupyter Notebook, Google Colab |
| Reporting            | PDF Reports                    |
| Presentation         | PowerPoint                     |
| Version Control      | Git & GitHub                   |

---

## Dataset Summary

| Metric             | Value  |
| ------------------ | ------ |
| Total Customers    | 7,043  |
| Total Features     | 21     |
| Target Variable    | Churn  |
| Churned Customers  | 1,869  |
| Retained Customers | 5,174  |
| Overall Churn Rate | 26.54% |

---

## Key Insights

### 1. High Churn Concentration

* 26.54% of customers left the company.
* More than one out of every four customers churned.

### 2. Contract Type is the Strongest Driver

Customers with Month-to-Month contracts exhibited the highest churn levels.

Long-term contract customers demonstrated significantly higher retention rates.

### 3. Tenure Strongly Influences Retention

Customers who churn typically leave within the early stages of their lifecycle.

Long-tenure customers showed substantially lower churn rates.

### 4. Billing Behavior Matters

Customers paying through Electronic Check experienced significantly higher churn compared to customers using automatic payment methods.

### 5. Service Adoption Reduces Churn

Customers using:

* Online Security
* Tech Support
* Device Protection

showed noticeably lower churn rates.

### 6. Fiber Customers Need Attention

Fiber Optic users displayed higher churn levels compared to DSL customers.

### 7. Gender Has Minimal Impact

Male and Female customers demonstrated nearly identical churn behavior.

---

## Data Cleaning Process

The dataset was cleaned and validated before analysis.

### Cleaning Steps Performed

* Replaced blank values in TotalCharges
* Converted TotalCharges to numeric datatype
* Checked missing values
* Verified duplicate records
* Validated Customer ID uniqueness
* Transformed SeniorCitizen from numeric encoding into categorical values
* Performed consistency checks across key fields

---

## Analysis Workflow

### Step 1 — Data Inspection

* Dataset dimensions
* Data types
* Missing values
* Duplicate analysis

### Step 2 — Data Cleaning

* Handling blank values
* Type conversions
* Data validation

### Step 3 — Feature Engineering

* Senior Citizen transformation
* Category standardization

### Step 4 — Exploratory Data Analysis

#### Customer Analysis

* Churn Distribution
* Gender Analysis
* Senior Citizen Analysis

#### Behavioral Analysis

* Contract Analysis
* Tenure Analysis
* Payment Method Analysis

#### Service Analysis

* Internet Services
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming Services

#### Financial Analysis

* Monthly Charges
* Total Charges

#### Correlation Analysis

* Numerical relationship assessment

---

## Visualizations Included

### Churn Distribution

Shows the overall percentage of customers who stayed versus customers who left.

### Gender vs Churn

Analyzes churn behavior across genders.

### Senior Citizen Analysis

Evaluates churn risk among senior customers.

### Contract Analysis

Highlights how contract duration influences retention.

### Tenure Analysis

Demonstrates customer lifecycle behavior.

### Service Dashboard

Analyzes:

* Internet Services
* Security Services
* Backup Services
* Streaming Services
* Payment Methods

### Financial Analysis

* Monthly Charges vs Churn
* Total Charges vs Churn

### Correlation Matrix

Identifies numerical relationships between variables.

---

## Customer Segmentation

### High-Risk Customers

Characteristics:

* Month-to-Month Contract
* Low Tenure
* Electronic Check Payments
* No Online Security
* No Tech Support
* Higher Monthly Charges

### Medium-Risk Customers

Characteristics:

* One-Year Contract
* Moderate Tenure
* Partial Service Adoption

### Low-Risk Customers

Characteristics:

* Two-Year Contract
* Long Tenure
* Automatic Payments
* Security & Support Services Enabled

---

## Business Impact

The analysis suggests that retention efforts should focus on customers who exhibit early churn signals.

Potential business outcomes include:

* Improved customer retention
* Increased customer lifetime value
* Reduced acquisition costs
* Higher recurring revenue
* Better service adoption rates

---

## Strategic Recommendations

### Contract Conversion Campaign

Encourage Month-to-Month customers to migrate to annual plans through discounts and loyalty incentives.

### Early Lifecycle Retention Program

Implement onboarding campaigns targeting customers within their first 12 months.

### Service Bundle Optimization

Bundle:

* Online Security
* Device Protection
* Tech Support

to improve retention.

### Payment Method Optimization

Promote automatic payment options and reduce dependency on Electronic Check payments.

### Fiber Customer Retention Strategy

Investigate customer experience issues among Fiber Optic subscribers and develop targeted retention campaigns.

---

## Repository Structure

```text
telecom-customer-churn-analysis/
│
├── data/
│   ├── raw/
│   │   └── Customer Churn.csv
│   │
│   └── cleaned/
│       └── Telecom_Customer_Churn_Cleaned.csv
│
├── images/
│   ├── Correlation Matrix.png
│   ├── Count of Customers by Churn.png
│   ├── Count of Customers by Gender and Churn.png
│   ├── Count of Customers by Tenure and Churn.png
│   ├── Count of Customers by Contract.png
│   ├── Monthly Charges by Churn.png
│   ├── Percentage of Customers by Churn.png
│   ├── Percentage of Customers by SeniorCitizen.png
│   ├── Total Charges by Churn.png
│   └── service_vs_churn_dashboard.png
│
├── notebooks/
│   ├── Telecom_Customer_Churn_EDA.ipynb
│   └── Telecom_Customer_Churn_EDA.pdf
│
├── presentation/
│   ├── Telecom_Customer_Churn_Insights.pptx
│   └── Telecom_Customer_Churn_Insights.pdf
│
├── report/
│   ├── Telecom_Customer_Churn_Analysis_Report.pdf
│   └── Telecom_Customer_Churn_Executive_Report.pdf
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Installation

```bash
git clone https://github.com/your-username/telecom-customer-churn-analysis.git

cd telecom-customer-churn-analysis

pip install -r requirements.txt
```

---

## Requirements

```text
pandas
numpy
matplotlib
seaborn
jupyter
```

---

## Project Deliverables

* Cleaned Dataset
* Jupyter Notebook
* Visualizations
* Business Insights
* Executive Report
* PowerPoint Presentation
* GitHub Documentation

---

## Author

### Pratik

Data Analytics | Python | SQL | Power BI | Tableau | Business Analytics

---

## License

This project is intended for educational, portfolio, and professional demonstration purposes.
