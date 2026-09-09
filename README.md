# 📊 Telco Customer Churn Analysis And Revenue Forecasting

<img width="965" height="541" alt="image" src="https://github.com/user-attachments/assets/53ff773c-cc67-4c3c-b9b9-7b3c3cd117a7" />


## 📁 Project Overview

This project analyzes customer churn in a telecommunications company to identify key drivers of churn, forecast future revenue impact, and develop data-driven retention strategies.  
It combines **SQL, Python, and Power BI** for a full data pipeline — from raw data extraction to advanced analytics and executive-level visualization.

---

## 🎯 Objectives

- Understand **why customers churn** and identify at-risk segments.  
- Build **predictive and financial models** to estimate churn and its revenue impact.  
- Develop **actionable strategies** for retention and revenue optimization.  
- Present insights in an **interactive Power BI dashboard** for business leaders.

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|----------|
| **Python (Pandas, NumPy, Scikit-Learn)** | Data cleaning, feature engineering, churn modeling |
| **SQL (PostgreSQL / MySQL)** | Data extraction, aggregation, and KPI computation |
| **Power BI** | Executive dashboards, churn prediction visualization, forecasting |
| **Excel** | Exploratory data review and validation |
| **GitHub** | Project versioning and portfolio publication |

---

## 🧩 Data Pipeline

Raw Telco Data → SQL Cleaning → Python Modeling → Power BI Visualization → Strategic Insights


1. **Data Cleaning & Transformation**
   - Removed duplicates and nulls from `TotalCharges`.
   - Standardized categorical fields and encoded binary attributes.
   - Calculated new metrics such as `AvgMonthlyRevenue`, `CLV`, and `ChurnRate`.

2. **SQL Analysis**
   - Aggregated churn by contract, payment method, and tenure.
   - Segmented customers by revenue and churn behavior.
   - Calculated revenue retention under various churn scenarios.

3. **Predictive Modeling (Python)**
   - Built a logistic regression model to predict churn probability.
   - Evaluated using accuracy, precision, recall, and ROC-AUC metrics.
   - Exported predictions for visualization in Power BI.

4. **Power BI Reporting**
   - Designed a 5-page interactive dashboard with executive KPIs, churn analysis, and revenue forecasting.

---

## 📊 Power BI Dashboard Overview

The Power BI report consists of **5 pages**, each designed for specific business decisions:

### 1. 🏢 Executive Overview
High-level company performance snapshot with KPIs:
- Total Customers, Active vs Churned
- Churn Rate (%)
- Average Tenure
- Monthly & Total Revenue

### 2. 🔍 Churn Predictions
Machine learning-powered churn probability visualization:
- Filters by gender, contract, and payment type
- Top churn drivers identified using feature importance
- At-risk customer segments highlighted

### 3. 📈 Revenue Forecast
Predicts future revenue based on historical trends and churn rate.
- Time-series forecasting using Power BI’s analytics pane
- Comparison of baseline vs retention-improved revenue scenarios

### 4. 💰 Customer Lifetime Value (CLV)
Segments customers by their lifetime value contribution:
- CLV tiers (High / Medium / Low)
- Relationship between CLV, tenure, and churn probability
- Focus on high-value churners for retention targeting

### 5. 🧮 Revenue Strategy Simulation
Interactive “what-if” analysis to simulate revenue impact of:
- Retention improvements
- Contract upgrades
- Customer loyalty programs

---

## 🔍 Key Insights & Findings

- **Overall churn rate:** 26.5% of customers have churned.  
- **Contract type:** Month-to-month customers are **2.4× more likely** to churn.  
- **Payment method:** Electronic check users churn **30% faster** than other groups.  
- **Tenure:** Customers with <12 months tenure represent **60% of all churns**.  
- **CLV impact:** High-value customers contribute **over 60% of total revenue**, making them critical for retention.  
- **Forecast insight:** A 5% improvement in retention leads to **~12% increase in annual revenue**.  

These insights guide retention strategies focused on contract conversion, early engagement, and loyalty incentives.

---

## 📈 Results Summary

| Metric | Value | Description |
|--------|--------|-------------|
| Churn Rate | 26.5% | Percentage of customers lost |
| Retention Improvement Potential | +5% | From targeted contract & payment fixes |
| Forecasted Revenue Uplift | +12% | Annual projection with improved retention |
| Model Accuracy | 83% | Logistic regression churn model |
| CLV Uplift | +18% | From focus on high-value customers |

---

## 🧩 Project Structure
```bash
Telco-Churn-Analysis/
│
├── data/
│   ├── raw/ WA_Fn-UseC_-Telco-Customer-Churn # Original CSV dataset
│   ├── processed/cleaned_customers           # Cleaned data for modeling and Power BI
│
├── notebooks/
│   ├── 01_data_import.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_chun_modelling.ipynb
│   ├── 04_revenue_forecast.ipynb
│
├── sql/
│   ├── churn_project.sql   # SQL queries for churn, CLV, revenue segmentation
│
├── scripts/
│   ├── db_config.py         # Database configuration
│   ├── db_connection.py     # Connection handler
│   ├── generate_revenue.py   # Preprocessing and feature engineering scripts
│
├── powerbi/
│   ├── Telco_Churn_Analysis.pbix   # Power BI Dashboard file
│
├── reports/
│   ├── Telco_Churn_Analysis_Report.pdf
│
├── README.md
└── requirements.txt

```
---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/yourusername/Telco-Churn-Analysis.git
```
2. Navigate to the folder
```bash
cd Telco-Churn-Analysis
```
3. Install dependencies
```bash
pip install -r requirements.txt
```
4. Open the notebooks in Jupyter or VSCode
jupyter notebook

### 🧠 STEP 2: Replace Before Commit

Before you commit:
1. Replace  
   - `https://app.powerbi.com/your_dashboard_link` → your published Power BI report link  
   - `yourusername`, `your_email@example.com`, and LinkedIn link.  
2. Keep the **triple backticks (\`\`\`)** around code blocks — GitHub formats them automatically.  
3. Commit using:
   ```bash
   git add README.md
   git commit -m "Add project documentation"
   git push

---

## ⭐ Project Highlights

✅ End-to-end data analysis: from SQL → Python → Power BI

✅ Predictive churn modeling integrated into visualization

✅ Strategic simulation of retention impact

✅ Ready for presentation to executives or recruiters

“Data without interpretation is just noise; turning churn analytics into action is what drives value.”

## 📘 References

Kaggle: [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)

Power BI Documentation – Forecasting and Analytics

Scikit-Learn Logistic Regression Reference


---




