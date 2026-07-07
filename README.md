# 📊 Superstore Sales & Profit Analysis Dashboard (2014–2017)

## 📌 Project Overview

This project is an end-to-end Business Intelligence solution built using Power BI to analyze sales, profitability, customer behavior, and product performance for a retail Superstore dataset.

The objective of the project is not only to build an interactive dashboard but also to uncover actionable business insights through exploratory and diagnostic analysis.

The report consists of three analytical pages:

- Executive Dashboard
- Business Insights & Recommendations
- Product Performance Analysis

---

## 🎯 Business Objectives

- Analyze overall sales and profitability
- Monitor Year-over-Year (YoY) business performance
- Identify high-performing and underperforming products
- Understand regional sales and profit distribution
- Analyze customer and segment performance
- Investigate factors affecting profitability
- Generate actionable business recommendations

---

## 🛠️ Tech Stack

- Power BI Desktop
- Power Query
- DAX
- Excel (Dataset)
- Data Modeling
- Data Visualization

---

## 📂 Data Preparation

The dataset was cleaned and transformed using Power Query. Key preparation steps included:

- Removed unnecessary columns
- Handled missing values
- Standardized data types
- Created a Date Dimension table
- Built relationships using a star schema
- Created calculated columns where required

---

## 📈 DAX Measures Created

| Measure | Description |
|---------|-------------|
| Total Sales | Sum of all sales |
| Total Profit | Sum of all profit |
| Total Orders | Count of distinct orders |
| Profit Margin % | Profit / Sales × 100 |
| Average Order Value | Sales / Total Orders |
| Previous Year Sales | SAMEPERIODLASTYEAR sales |
| YoY Sales Growth % | (Current - Previous) / Previous × 100 |
| Average Profit per Order | Profit / Total Orders |
| Average Sales per Order | Sales / Total Orders |
| Highest Product Profit | Max profit by product |
| Highest Product Loss | Min profit by product |
| Loss-Making Products Count | Count of products with negative profit |

---

## 📊 Dashboard Pages

### 📌 Page 1 – Executive Dashboard
Provides a high-level overview of business performance.

**KPIs:** Total Sales · Total Orders · Profit Margin % · Average Order Value · YoY Growth Metrics

**Visuals:**
- Top 5 Profit Cities
- Profit by Region
- Top 5 Profit Sub-Categories
- Top Customers
- Monthly Sales & Profit Trend
- Sales by Segment

---

### 📌 Page 2 – Business Insights & Recommendations
Focuses on diagnosing business performance through data analysis.

Key areas analyzed:
- Regional Performance
- South Region Investigation
- Furniture Profitability
- Customer & Segment Analysis
- Binder Sales Spike (Q4 2016)
- Business Recommendations

---

### 📌 Page 3 – Product Performance Analysis
Analyzes product profitability and discount impact.

Includes:
- Product KPIs
- Top 10 Loss-Making Products
- Discount vs Profit Analysis
- Profit Margin by Sub-Category
- Regional Contribution to Product Losses

---

## 🔍 Key Business Insights

### 📍 Regional Performance
- West generated the highest overall sales and profits
- South recorded the lowest sales performance
- West region profit ($108K) outperformed Central region by 173%

### 💰 Furniture Performance
- Furniture generated the lowest overall profit ($18.45K)
- Tables alone recorded a net loss of $17.73K despite $206K in sales
- Higher discounts were associated with weaker profit margins in several furniture products

### 📉 Discount Analysis
- Products receiving unusually high discounts generally exhibited weaker profit margins
- High-discount products should be reviewed to improve profitability

### 👥 Customer Insights
- Consumer segment generated the highest sales
- Home Office customers achieved the highest average profit per order ($66.34)
- Top 10 customers contributed only 6.7% of total sales — indicating a healthy, diversified customer base

### 📦 Product Insights
- Several products generated high sales but remained unprofitable
- Premium technology products and conference tables contributed significantly to product losses

### 📈 Trend Analysis — Binder Sales Q4 2016
- Sales increased ~250% from November to December 2016
- The increase was driven by higher-value transactions, not order volume
- Average sales per order jumped from $91 → $383
- Average profit per order jumped from $19 → $159

---

## 💡 Business Recommendations

- ✔ Review discount strategies for high-discount, low-margin products
- ✔ Reduce losses from underperforming furniture products — cap discounts on Tables below 15%
- ✔ Increase focus on higher-margin product categories like Copiers and Technology
- ✔ Monitor products generating high sales but negative profits
- ✔ Optimize pricing strategies for premium technology products
- ✔ Develop targeted strategies for the Home Office segment — high profit per order but low order volume

---

## 🧠 Executive Summary

Superstore achieved strong revenue growth of 46.88% YoY, driven primarily by the Consumer segment and the West region. However, profitability is being undermined by aggressive discounting in Furniture — particularly Tables, which recorded a net loss of $17.73K despite $206K in sales — and by underperformance in the South region. Addressing discount strategies in low-margin sub-categories and shifting focus toward high-value Technology and Copier products presents the clearest path to sustainable profit growth.

---

## 📷 Dashboard Preview

| Page 1 | Page 2 | Page 3 |
|--------|--------|--------|
| ![Executive Dashboard](Dashboard%20Screenshots/Executive%20Dashboard.png) | ![Insights](Dashboard%20Screenshots/Insights%20%26%20Recommendations.png) | ![Product Analysis](Dashboard%20Screenshots/Product%20Analysis.png) |

---

## 📁 Repository Structure

```
Superstore-Sales-Dashboard/
│
├── Dataset/
│   └── Superstore.xlsx
│
├── Dashboard Screenshots/
│   ├── Executive Dashboard.png
│   ├── Insights & Recommendations.png
│   └── Product Analysis.png
│
├── Superstore Dashboard.pbix
│
└── README.md
```

---

## 🚀 Skills Demonstrated

`Data Cleaning` `Data Modeling` `DAX` `Power Query` `Dashboard Design` `Business Intelligence` `Exploratory Data Analysis` `Diagnostic Analytics` `Data Visualization` `Business Storytelling` `KPI Design` `Analytical Thinking`

---

## 📬 Contact

**Sriram B**

- GitHub: [Sriram14890](https://github.com/Sriram14890)
- LinkedIn: *(Add your LinkedIn profile link)*

---

⭐ If you found this project interesting, consider giving this repository a star!
