# 📊 Blinkit Sales Analysis Dashboard

## 🧾 Overview
This repository provides a **Blinkit Sales Analysis Dashboard** built using **Power BI**, **SQL**, and **Python**. It analyzes Blinkit’s sales performance, customer satisfaction, and inventory distribution to identify actionable insights and optimization opportunities.

---

## 🎯 Business Requirement
Conduct a detailed analysis of Blinkit’s **sales performance**, **customer satisfaction**, and **inventory distribution** to generate key insights using various KPIs and Power BI visualizations.

---

## ⚙️ Tools & Technologies
- **Power BI** → Data visualization and dashboard creation  
- **SQL** → Data extraction, transformation, and aggregation  
- **Python (Pandas, NumPy, Matplotlib)** → Data cleaning and preprocessing  

---

## 📌 Key Performance Indicators (KPIs)

| KPI | Description |
|------|--------------|
| **Total Sales** | Overall revenue generated from all items sold |
| **Average Sales** | Average revenue per sale |
| **Number of Items** | Total count of distinct items sold |
| **Average Rating** | Average customer rating for items sold |
---

## 📊 Power BI Visualizations

| # | Visualization                           | Objective                                                   | Chart Type           |
| - | --------------------------------------- | ----------------------------------------------------------- | -------------------- |
| 1 | **Total Sales by Fat Content**          | Analyze impact of fat content on total sales                | Donut Chart          |
| 2 | **Total Sales by Item Type**            | Identify performance of item types                          | Bar Chart            |
| 3 | **Fat Content by Outlet (Total Sales)** | Compare total sales across outlets segmented by fat content | Stacked Column Chart |
| 4 | **Total Sales by Outlet Establishment** | Evaluate influence of outlet age/type on total sales        | Line Chart           |
| 5 | **Sales by Outlet Size**                | Correlation between outlet size and total sales             | Donut / Pie Chart    |
| 6 | **Sales by Outlet Location**            | Assess geographic sales distribution                        | Funnel Map           |

---

## 🧭 Dashboard Features

* Interactive slicers: **Date, Item Type, Fat Content, Outlet Size**
* Drillthrough pages for item-level insights
* Dynamic tooltips showing KPIs
* Bookmarks for storytelling and comparisons

---

## 📁 Folder Structure

```bash
Blinkit-Sales-Analysis/
├─ data/
│  ├─ raw/
│  └─ processed/
├─ sql/
│  └─ analysis_queries.sql
├─ python/
│  └─ data_cleaning.ipynb
├─ powerbi/
│  └─ Blinkit_Report.pbix
└─ README.md
```

