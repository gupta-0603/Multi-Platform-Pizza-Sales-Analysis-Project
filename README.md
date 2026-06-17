# 🍕 Pizza Sales Analysis - Multi-Platform Data Project

This repository showcases an end-to-end data analysis project focusing on pizza sales performance metrics. To demonstrate modern data engineering, analysis, and visualization workflows, the project has been fully built across four distinct platforms: **Power BI, Python (Jupyter Notebook), Excel, and Tableau**.

---

## 📌 Project Workflow
Data Source (.csv) ➡️ Data Cleaning & EDA (Python) ➡️ Multi-Platform Analysis & Interactive Dashboards (Power BI | Tableau | Excel)

---

## 🚀 Project Assets & Interactive Links
* 📊 **Power BI Report:** [Download & View .pbix File](./powerbi/pizza_sales_report.pbix) *(Download to view full interactive DAX model)*
* 📈 **Tableau Public Dashboard:** [View Interactive Tableau Dashboard]([PASTE_YOUR_TABLEAU_PUBLIC_LINK_HERE])
* 🐍 **Python Analysis:** [View Jupyter Notebook Workspace](./eda/pizza_analysis.ipynb)
* 📁 **Excel File:** [Download Excel Dashboard](./excel/pizza_sales_dashboard.xlsx)
---

## 📊 Core Performance Metrics (KPIs)
Based on the full year of data analyzed (Jan 2015 - Dec 2015), the business achieved the following foundational metrics:
* **Total Revenue:** $817.86K
* **Average Order Value:** $38.31
* **Total Pizzas Sold:** 50K
* **Total Orders:** 21K
* **Average Pizzas Per Order:** 2.32

---

## 🔧 Platform Implementations

### 1. Python (Jupyter Notebook)
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`
* **Key Steps:** Data profiling, handling schema types, extraction of date/time fields, and verifying quantitative aggregation metrics against BI data models.

### 2. Power BI Dashboard
* **Techniques:** Engineered dynamic DAX measures for KPIs, configured time-intelligence functions, implemented dynamic navigation tabs, and established custom conditional filtering.

### 3. Excel Interactive Dashboard
* **Techniques:** Handled extraction transformations via Power Query, designed multi-layer Pivot Tables, and synced interactive slicers across the workspace.

### 4. Tableau Dashboard
* **Techniques:** Implemented discrete dimension tracking, dual-axis progression trendlines, and customized tooltip parameters.

---

## 🧠 Key Data Insights & Inferences

### 📅 Busiest Days & Times
* **Daily Trend:** Orders peak significantly on weekends, with **Friday and Saturday evenings** experiencing the highest transaction volumes.
* **Monthly Trend:** The business experiences maximum order volumes during the months of **July and January**.

### 🍕 Category & Size Performance
* **Pizza Category:** The **Classic category** is the top performer, contributing the maximum sales revenue and total orders.
* **Pizza Size:** **Large size pizzas** dominate customer preferences, driving the maximum overall sales distribution.

### 🏆 Best Sellers (Top 5)
* **By Revenue:** *The Thai Chicken Pizza* leads with highest revenue generation ($43K), closely followed by *The Barbecue Chicken Pizza*.
* **By Quantity & Total Orders:** *The Classic Deluxe Pizza* ranks #1 across both total quantities sold (~2.5K) and total unique orders (~2.3K).

### ⚠️ Worst Sellers (Bottom 5)
* **By Revenue, Quantity, & Total Orders:** *The Brie Carre Pizza* is the lowest performer across all dimensions, generating minimum revenue ($11.6K), lowest quantities sold (~490), and lowest total orders (~480).

---

## 🖥️ Dashboard Previews & Screenshots

### 🖼️ Power BI - Home Dashboard View
Below is the core executive layout featuring total revenue distribution, volume trends, and structural breakdowns by category and size.
![Power BI Home Dashboard](./screenshots/powerbi_home.png)

### 🖼️ Power BI - Best / Worst Sellers View
Below is the specialized performance breakout tracking top-tier and underperforming pizza menu items.
![Power BI Performance Dashboard](./screenshots/powerbi_sellers.png)

### 🖼️ Tableau Dashboard Preview
![Tableau Dashboard Screenshot](./screenshots/tableau_dashboard.png)

### 🖼️ Excel Dashboard Preview
![Excel Dashboard Screenshot](./screenshots/excel_dashboard.png)

### 🖼️ Python EDA Visualization Preview
![Python Seaborn Plot Screenshot](./screenshots/python_eda.png)

---

## 🛠️ Tools & Technologies Used
* **Languages:** Python, DAX (Power BI)
* **Visualization Platforms:** Power BI Desktop, Tableau Public, Microsoft Excel
* **Environment:** Jupyter Notebook
