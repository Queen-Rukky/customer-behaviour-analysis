# 🛒 Customer Retail Analysis Project

**Comprehensive Analysis of 20,000 Customer Transactions**  
**End-to-End Data Pipeline:** Python | MySQL | Power BI
---

## 📌 Project Overview

This project demonstrates a full **end-to-end data analytics workflow**, transforming messy retail transaction data into actionable business insights. The analysis covers data cleaning, exploratory analysis, SQL-based insights, and interactive visualization using Power BI.

The goal is to understand **customer behavior, product performance, discount effectiveness, and geographic trends** to support data-driven business decisions.

## Dashboard
<img width="1190" height="689" alt="Screenshot 2026-02-02 193207" src="https://github.com/user-attachments/assets/4ca89589-c2c2-433b-a219-7b03e5a9c63b" />

## 🎯 Objectives

- Analyze customer purchasing behavior
- Identify high-value customer segments
- Evaluate the impact of discounts on revenue
- Discover top-performing products and regions
- Provide data-driven business recommendations

---

## 📂 Dataset Information

| Attribute | Details |
|---------|--------|
| Dataset Name | `messy_retail_dataset_20000_rows.csv` |
| Total Records | 20,000 transactions |
| Total Columns | 22 |
| Missing Values | 45,259 cells (≈11.27%) |
| Data Type | Historical retail transaction data |

---

## 🧰 Technology Stack

- **Python** (Pandas, NumPy, Seaborn, Matplotlib) – Data cleaning & EDA  
- **MySQL** – Data storage and SQL analysis  
- **Power BI (DAX)** – Interactive dashboards & KPIs  
- **Microsoft Excel** – Documentation & reference tables  

---

## 🧹 Data Cleaning Summary (Python)

### Key Steps

- Standardized column names (removed spaces & special characters)
- Removed duplicate records
- Handled **45,259 missing values**
- Created new engineered features:
  - `Age_Group` (quartile-based segmentation)
  - Purchase frequency metrics

### Tools Used

- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  

---

## 📊 Exploratory Data Analysis (EDA)

### Key Statistics

- **Average Purchase Amount:** $1,001.13  
- **Age Range:** 16 – 69 years  
- **Average Review Rating:** 3.0 / 5  
- **Average Previous Purchases:** 24  

### Key Insights

- 21–40 age group is the highest spending demographic
- Shirts generate the highest revenue among all products
- Discounts are widely used but reduce average spend slightly
- Delivery delays average 6 days

---

## 🗄️ SQL Analysis (MySQL)

- **Database:** `clean_retail`
- **Table:** `clean_retail`
- **Total Queries Executed:** 13

### Sample Business Questions Answered

- Which customers spend above average despite using discounts?
- Which age group generates the most revenue?
- What products drive the highest revenue?
- How does discount usage vary by location?

### Example Query

```sql
SELECT
    Discount_Applied,
    AVG(Purchase_Amount_USD) AS avg_spend
FROM clean_retail
GROUP BY Discount_Applied;

## 📈 Power BI Dashboard & DAX

### KPIs

- **Total Revenue:** $20.02M  
- **Total Customers:** 20,000  
- **Average Transaction Value:** $1,001.13  
- **Discount Usage Rate:** ~26.7%  

### Visuals Included

- Revenue by Customer Segment  
- Top Products by Revenue  
- Geographic Revenue Distribution  
- Discount Impact Analysis  
- Seasonal Trends  
- Payment Method Breakdown  

### Key DAX Measures

- Total Revenue  
- Average Transaction Value  
- Customer Retention Rate  
- VIP Customer Revenue  
- Discount Revenue Impact  

---

## 💡 Business Recommendations

- Focus marketing on the **21–40 age group**
- Strengthen **VIP customer loyalty programs**
- Increase inventory for **Shirts** (top revenue product)
- Use **targeted, tiered discounts** instead of blanket discounts
- Reduce delivery delays to improve customer satisfaction
- Localize pricing and promotions by region  

---

## 🚀 Key Outcomes

- Cleaned and standardized **20,000 records**
- Identified **$1.15M revenue opportunity** in a single product category
- Revealed **6.6% higher spending** among VIP customers
- Built a fully interactive **Power BI dashboard**
- Delivered actionable, data-backed business insights  

---

## 🔮 Future Enhancements

- Predictive modeling for churn and customer lifetime value (CLV)
- Time-series forecasting for demand planning
- NLP-based sentiment analysis on customer comments
- Recommendation engine using purchase history
- Automated reporting workflows  

---

## 📌 Conclusion

This project showcases strong **data analytics, SQL, and business intelligence skills**, demonstrating how raw data can be transformed into strategic insights. It reflects real-world analytics workflows used in modern retail and business environments.

---

## 👤 Author

**Rukayat Obanor**  
Data Analyst | Business Intelligence | SQL | Power BI  

📫 Open to remote data analyst opportunities



