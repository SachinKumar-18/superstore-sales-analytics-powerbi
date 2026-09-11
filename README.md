# Retail Sales Performance Dashboard

An interactive, single-page Power BI dashboard built on the Superstore retail dataset, 
analyzing sales, profit, regional distribution, and discount impact across 4,200 orders 
from 2022–2025.

## 📊 Project Overview
Built as part of *Data Analytics Essentials with AI* (Course Code: PETV103).
Full workflow: data cleaning → transformation → EDA → dashboard design → business insights.

## 🎯 Objectives
- Analyze sales and profit performance (2022–2025)
- Identify top-performing and loss-making categories
- Study regional/state-wise variation
- Examine discount vs. profitability relationship
- Build a single-page interactive Power BI dashboard

## 🗂 Dataset
- **Source:** [Kaggle – Superstore Sales Dataset](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)
- **Size:** 4,200 order-line records
- **Fields:** Order ID, Order/Ship Date, Customer, Segment, Region/State/City, 
  Category/Sub-Category, Sales, Quantity, Discount, Profit, Ship Mode

## 🛠 Tools Used
- **Microsoft Excel** — data cleaning & preparation
- **Microsoft Power BI Desktop** — data modeling, DAX measures, dashboard design

## 📈 Dashboard Features
- KPI cards: Total Sales, Total Profit, Total Orders, Profit Margin, Avg Order Value, Avg Discount
- Sales trend over time (line chart)
- Sales by region, state (filled map), category, sub-category
- Discount vs. profit margin scatter chart
- Segment & ship mode breakdown (donut charts)
- Performance matrix table
- Slicers: Order Year, Region, Category, Segment, Ship Mode + Reset Filters button

## 🔑 Key Findings
- Total sales: **$10.04M** | Total profit: **$1.39M** | Margin: **13.86%**
- Technology leads in sales ($6.76M) and strong margin (17.11%)
- **Furniture generates $2.22M in sales but only 2.39% margin** — driven by heavy discounting (biggest insight)
- Regional sales are evenly balanced (no single dominant region)

## 💡 Recommendations
- Cap discounts on Furniture sub-categories (Tables, Bookcases)
- Expand Technology sub-categories (Copiers, Machines)
- Introduce loyalty incentives for the Consumer segment

## 📁 Files in this Repo
- `Superstore_Raw_and_Cleaned.xlsx` — raw and cleaned data (2 sheets)
- `Retail_Sales_Dashboard.pbix` — Power BI dashboard file (open with Power BI Desktop)
- `Project_Report.pdf` — full written project report

## 👤 Author
[SACHIN KUMAR]

## 📄 License
Dataset used under Kaggle's public/educational license.
