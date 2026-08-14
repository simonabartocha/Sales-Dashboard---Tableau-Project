# 📊 Sales & Customer Dashboard – Tableau Project

An interactive sales and customer dashboard built in Tableau, presenting
sales and customer data analysis covering the years 2020–2023.

This project was created as part of the course:
**Tableau Ultimate Full Course - From Zero to HERO**

The core part of the project (Sales Dashboard) was built following the
course material, while **the Customer Dashboard is my own independent
extension**, going beyond the scope of the course — designed and built
entirely from scratch as an expansion of the analysis with a customer
perspective.

## 📁 Data Source

Data based on the Superstore dataset, consisting of four related tables:

| Table | Description |
|---|---|
| Orders | Orders – sales, profit, quantity, discounts |
| Customers | Customer data and segments |
| Products | Product categories and subcategories |
| Location | Geographic locations of orders |

## ✅ Completed Scope

### 1. Sales Dashboard
- **KPI Cards** – Total Sales, Total Profit, Total Quantity with
  year-over-year comparison (% vs PY)
- Highlighting of the best and worst performing months
  (Highest / Lowest Month)
- **Sales & Profit by Subcategory** – 2023 vs 2022 comparison with
  profit/loss indicators
- **Sales & Profit Trends over Time** – monthly trends with an average
  reference line
- Expandable filter/legend panel (see screenshot #3) with full control
  over displayed metrics:
  - **Select Year** – dropdown to dynamically switch the year displayed
    across all views
  - **Measure Names filter** – toggle individual measures on/off:
    - Min/Max Sales – highlights the best and worst sales months
    - Min/Max Profit – highlights the best and worst profit months
    - Min/Max Quantity – highlights the best and worst quantity months
    - CY Profit – current year profit bars (scale up to ~$35K)
    - CY Sales – current year sales bars (scale: $1K–$35K)
    - KPI Profit Avg – reference line showing average profit threshold
      
 ![Sales Dashboard](./Sales%20Dashboard%20Tableu.png)

### 2. Customer Dashboard *(own extension – beyond course scope)*
- **KPI Cards** – Total Customers, Avg Sales per Customer, New Customers
  (% of new customers for the year) with year-over-year comparison
- Highlighting of the best and worst performing months for each metric
- **Customer Segmentation** – treemap of customer segments (Consumer,
  Corporate, Home Office) broken down by product category (Technology,
  Furniture, Office Supplies) with sales values
- **Customer Distribution by Region** – interactive US map showing
  customer count per state, with the top state highlighted

![Customers Dashboard](./Customers%20Dashboard%20Tableu.png)

## 🧮 Calculated Fields (selected)

- Current Year / Previous Year – dynamic year filtering
- % Diff Sales, % Diff Profit, % Diff Quantity – year-over-year growth
- KPI Sales Avg, KPI Profit Avg, KPI CY Less PY – performance indicators
- Min/Max Sales, Min/Max Profit, Min/Max Quantity – highlighting extreme
  months

![Functions change](./Functions%20change%20Tableu.png)

## 🛠️ Tools & Technologies

- Tableau Desktop / Tableau Public
- Raw data in .csv format

## 🎓 Course

The base part of this project (Sales Dashboard) was built as part of the
course: **Tableau Ultimate Full Course - From Zero to HERO**

## 📌 Project Status

Project completed. The Sales Dashboard was built following the course
material, while the Customer Dashboard is a fully independent extension,
designed and implemented separately from the course content.
