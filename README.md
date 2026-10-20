# 📊 Telco Customer Churn & Revenue Retention Analysis
**Google Data Analytics Capstone Project (Track B)**

## 📌 Executive Summary
Analyzed a dataset of 7,043 customer accounts for a telecommunications company to investigate drivers behind customer churn and identify high-risk revenue streams. 

* **Overall Churn Rate:** 26.54% (1,869 customers lost)
* **Monthly Revenue at Risk:** $139,130.85
* **Primary Key Driver:** Month-to-month contract holders account for 88.5% of total churned customers with a 42.71% individual churn rate.

---

## 🔍 Data Analysis Process (Google Analytics Framework)

### 1. Ask
* What factors contribute most significantly to customer churn?
* Which customer segments represent the highest monthly recurring revenue loss?
* What actionable business strategies can reduce churn and protect revenue?

### 2. Prepare & Process (Data Cleaning in Excel)
* Checked for missing values across 7,043 rows.
* Handled missing/blank entries in `TotalCharges` by converting data types to currency.
* Built dynamic Pivot Tables to cross-tabulate contract types, payment channels, and monthly charges against churn status.

### 3. Analyze (Key Findings)
* **Contract Risk:** Month-to-month contracts exhibit a **42.71% churn rate**, compared to **11.27%** for 1-year and **2.83%** for 2-year contracts.
* **Payment Method Friction:** Customers paying via **Electronic Check** represent the highest proportion of lost monthly revenue ($84,288.75 of $139.1K lost).

---

## 💡 Strategic Business Recommendations
1. **Onboarding Contract Upgrades:** Introduce a 15% promotional discount on the first 3 months to incentivize new users to sign 1-year contracts during onboarding.
2. **Autopay Migration Incentives:** Provide a $5 monthly bill credit for customers migrating from Electronic Check to automated bank or credit card payments.

---

## 📁 Repository Files
* `Telco-Customer-Churn.xlsx` — Excel Workbook with Pivot Tables and Charts.
* `Telco_Churn_Executive_Presentation.pdf` — Executive Slide Deck for Leadership.
