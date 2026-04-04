# 🚚 Supply Chain Risk & Performance Analysis — Delivery Delays & Supplier Efficiency

## Project Type

End-to-End Data Analytics Dashboard

---

## 🎯 Business Problem

Supply chain inefficiencies such as delivery delays, high-risk products, and inconsistent supplier performance can lead to revenue loss and operational disruptions.

This project aims to:
- Identify delay patterns across suppliers
- Detect high-risk products based on delivery time
- Analyze demand distribution for better inventory planning
- Improve supplier performance evaluation

---

## Overview

This project presents an interactive Power BI dashboard designed to analyze and optimize supply chain performance. It provides insights into demand distribution, supplier efficiency, delivery delays, and product risk levels.

---

## 🔄 Data Workflow

1. Raw supply chain dataset collected
2. Data cleaned and transformed using Python (Pandas)
3. Feature engineering performed for risk and delay metrics
4. Data loaded into Power BI for visualization
5. Interactive dashboard created for business decision-making

---

## Live Preview

Download the `.pbix` file and open it in Power BI Desktop to explore the interactive dashboard.

---

## Key Features

* KPI tracking (Profit, Demand, Delay %, High Risk Products)
* Demand analysis by product category
* Supplier performance based on delay percentage
* High-risk product identification using delivery time
* Interactive filters (Category & Supplier)
* Top N analysis and DAX-based measures

---

## ⚙️ Data Processing & Analysis (Python)

- Performed data cleaning using Pandas:
  - Handled missing values and inconsistent records
  - Standardized categorical fields (Supplier, Category)

- Engineered key features:
  - Delay Percentage = (Delayed Orders / Total Orders)
  - Risk Classification based on delivery time thresholds
  - Supplier Performance Score combining delay and demand metrics

- Conducted exploratory data analysis (EDA):
  - Identified distribution of demand across categories
  - Analyzed supplier-wise delay patterns
  - Detected correlation between delivery time and product risk

---

## Tools Used

* Power BI
* DAX (Data Analysis Expressions)
* Data Visualization

---

## 🚀 Business Impact

- Identified key suppliers contributing to delivery delays, enabling targeted performance improvements
- Highlighted high-risk products affecting supply chain stability
- Provided data-driven insights to improve inventory planning and reduce operational risk
- Created a scalable dashboard for continuous monitoring of supply chain performance

---

## 📊 Key Insights

- Grocery category shows consistently high demand, indicating strong consumption patterns and priority stocking needs
- Certain suppliers exhibit significantly higher delay percentages, highlighting operational inefficiencies
- High-risk products are strongly correlated with longer delivery times and supply instability
- Supplier performance variability suggests potential for optimization through better vendor selection
- Improving supplier efficiency and inventory planning can reduce delivery risk and increase overall profitability
- Identified strong correlation between delivery delays and high-risk product classification, indicating systemic supply chain inefficiencies

---

## Dashboard Preview

![Dashboard](dashboard.png)

---

## How to Use

1. Download the `.pbix` file from this repository
2. Open it using Power BI Desktop
3. Use slicers (Category & Supplier) to interact with the dashboard
4. Explore KPIs and visual insights

---
