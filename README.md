# 📊 Customer Segmentation using RFM Analysis

## 🚀 Project Overview

This project focuses on **Customer Segmentation using RFM (Recency, Frequency, Monetary) Analysis** using **Microsoft Power BI**. The objective is to analyze customer purchasing behavior, classify customers into meaningful segments, and provide business insights through an interactive dashboard.

The dashboard helps businesses identify **Loyal Customers, Regular Customers, New Customers, and Churn Risk Customers**, enabling data-driven marketing strategies and customer retention.

---

## 👩‍💻 Prepared By

**Natasha Avinash Gundaye**

---

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Microsoft Excel
- DAX (Data Analysis Expressions)
- Power Query

---

## 📂 Dataset

**Dataset:** Online Retail Dataset

The dataset contains customer transaction records, including:

- Invoice Number
- Invoice Date
- Customer ID
- Quantity
- Unit Price
- Country

A new column (**TotalAmount**) was created for sales calculations.

---

# 🎯 Project Objectives

- Import and clean transactional customer data.
- Calculate RFM metrics (Recency, Frequency, Monetary).
- Segment customers into different customer groups.
- Analyze customer purchasing behavior.
- Create interactive KPI cards and visualizations.
- Generate business insights and marketing recommendations.
- Build an interactive Power BI dashboard.

---

# 🧹 Data Cleaning

The following preprocessing steps were performed:

- Imported the dataset into Power BI.
- Removed blank Customer IDs.
- Removed returned transactions (Quantity ≤ 0).
- Removed records with Unit Price ≤ 0.
- Verified data types.
- Created **TotalAmount = Quantity × UnitPrice**.
- Ensured date columns were properly formatted.

---

# 📈 RFM Analysis

### 🕒 Recency (R)

Measures how recently a customer made their last purchase.

Lower Recency indicates a more active customer.

---

### 🔄 Frequency (F)

Measures how often a customer makes purchases.

Higher Frequency indicates better customer engagement.

---

### 💰 Monetary (M)

Measures the total amount spent by a customer.

Higher Monetary value indicates higher customer value.

---

# 👥 Customer Segmentation

Customers were classified into:

- ⭐ Loyal Customers
- 🔵 Regular Customers
- 🆕 New Customers
- ⚠️ Churn Risk Customers

---

# 📊 Dashboard Features

### KPI Cards

- 👥 Total Customers
- 💰 Total Revenue
- 📦 Total Orders
- 💵 Average Order Value
- 📅 Average Recency
- 🔄 Average Frequency
- 💳 Average Monetary
- ⭐ Loyal Customers
- 🆕 New Customers
- ⚠️ Churn Risk Customers

---

### Visualizations

- 🍩 Customer Segment Distribution (Donut Chart)
- 📊 Revenue by Customer Segment (Bar Chart)
- 📈 Average Purchase Frequency (Column Chart)
- 📉 Monthly Revenue Trend (Line Chart)
- 🌍 Top Countries by Revenue (Bar Chart)
- 🌳 Revenue Contribution (Treemap)
- 📋 Customer RFM Summary Table

---

# 🎛 Interactive Filters

The dashboard includes slicers for:

- Country
- Customer Segment
- Month

These filters allow users to explore customer behavior dynamically.

---

# 💡 Key Insights

- Loyal customers generate the highest revenue.
- Churn Risk customers require retention strategies.
- New customers have growth potential.
- Regular customers can be converted into Loyal customers through targeted campaigns.
- Revenue distribution varies across different customer segments and countries.

---

# 🎯 Marketing Recommendations

### ⭐ Loyal Customers

- VIP Membership Programs
- Loyalty Rewards
- Early Product Access

### 🆕 New Customers

- Welcome Discounts
- Personalized Product Recommendations
- Follow-up Email Campaigns

### 🔵 Regular Customers

- Bundle Offers
- Cross-selling
- Cashback Rewards

### ⚠️ Churn Risk Customers

- Win-back Campaigns
- Personalized Discounts
- Reminder Emails

---

# 🧠 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Calculations
- Power Query
- Customer Segmentation
- RFM Analysis
- KPI Development
- Dashboard Design
- Data Visualization
- Business Intelligence

---

# 📷 Dashboard Preview

> Add your dashboard screenshot below after uploading it.

<img width="1600" height="916" alt="1000324060" src="https://github.com/user-attachments/assets/131fcebc-08f9-45d0-83b2-af146a2674ff" />

---

# 📁 Project Structure

```
Syntecxhub_Customer_Segmentation_RFM_Analysis/
│
├── Customer_Segmentation_RFM.pbix
├── Customer_Segmentation_RFM_Report.pdf
├── dashboard.png
├── dataset/
│   └── Online Retail.csv
└── README.md
```

---

# 📌 Future Enhancements

- Customer Lifetime Value (CLV) Analysis
- Customer Churn Prediction using Machine Learning
- Product Recommendation System
- Real-time Dashboard Integration
- Automated Customer Segmentation

---

# ✅ Conclusion

This project demonstrates how **RFM Analysis** can be used to understand customer purchasing behavior and support business decision-making. By combining data cleaning, DAX calculations, customer segmentation, KPIs, and interactive visualizations, the dashboard provides meaningful insights that can improve customer retention and marketing effectiveness.

---

## 📬 Contact

**Name:** Natasha Avinash Gundaye

📧 Email: gundayenatasha12@gmail.com

🔗 LinkedIn: www.linkedin.com/in/natashasag06



---

## ⭐ If you found this project helpful, consider giving it a Star on GitHub!
