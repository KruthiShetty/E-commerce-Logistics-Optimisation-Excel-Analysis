# 📦 E-commerce Logistics Optimisation – Excel Analysis

## 🔍 Problem Statement
As a Logistics Analyst, the goal was to analyse delivery routes, compare logistics providers (**FASTWHEELS** and **SHIP2HOME**), and optimise the **shipping cost** and **delivery days** using Excel tools. Based on performance, order distribution was adjusted to improve operational efficiency.

---

## 🌐 Dataset Overview
`ecommerce_logistics.csv` contains fields such as:

- Order ID
- Logistics Provider ID
- Final Delivery Status  
- Dispatch Date, Actual Delivery Date, Promised Delivery Date  
- Shipping Cost, Transit Storage Cost  
- Origin City, Destination City, Product Category

**Focus**: Optimising shipping routes using FASTWHEELS and SHIP2HOME.

---

## 🎯 Activity 1: Excel Data Preparation & KPI Creation

### ✏️ Basic Formatting & Data Cleaning
- Dates formatted for readability (`dd-mmm-yyyy`)
- New calculated columns:
  - `Shipping Route = Origin City + Destination City`
  - `Delivery Days = Actual Delivery Date - Dispatch Date`
  - `Delay Days = Actual Delivery Date - Promised Delivery Date`

### 🔍📂 Data Aggregation
Used Pivot Tables to calculate:
- Average Delivery Days
- Average Shipping Cost
- Route-wise performance comparison between FASTWHEELS & SHIP2HOME

---

## 📈 Activity 2: Route Optimisation & What-If Analysis

### ✅ Categorisation of Shipping Routes

- **Category 1**: FASTWHEELS had both lower cost and faster delivery → 100% of orders assigned  
- **Category 2**: FASTWHEELS outperformed only in one metric → *Goal Seek* used to optimise delivery days (target: 4 days)  
- **Category 3**: SHIP2HOME outperformed or no clear winner → manual analysis applied  

### ⚙️ Tools Used
- Pivot Tables for summarising performance
- `IF`, `AVERAGEIFS`, `COUNTIFS`, `VLOOKUP` for KPIs and comparisons
- **Goal Seek** to identify ideal order split and delivery thresholds

---

## 📊 Activity 3: Dashboard Creation

A single-page **Excel Dashboard** was built using:

- **Pie Chart** – Product Category vs Order Volume
- **Bar Chart** – Source of Order Comparison
- **Clustered Bar Charts** – Cost and delivery time comparison (before & after optimisation)
- **Post-Optimisation Charts** – Order allocation, cost reduction, and delivery improvements

### 🎛️ Dashboard Interactivity
- **Slicers** for filtering by provider, route, and product category
- Uniform styling with colour-coded KPIs and chart formatting

---

## 🌟 Excel Features Used

- Pivot Tables  
- `IF`, `VLOOKUP`, `AVERAGEIFS`, `COUNTIFS`  
- Date arithmetic  
- Data Cleaning & Custom Columns  
- Interactive Dashboard with Slicers & Visuals  
- Chart Formatting (background colour, chart area, borders)

---

## 🚀 Summary

This project highlights how Excel can be used to **optimise logistics performance** by analysing KPIs such as delivery time and shipping cost. A data-driven approach was used to shift order allocation towards the more efficient provider (**FASTWHEELS**), improving both time and cost metrics. The final interactive dashboard enabled stakeholders to easily explore optimisation outcomes and make informed decisions.

---

## 👨‍💻 Author & Contact  
**Kruthi Shetty**  
[**LinkedIn Profile**](https://www.linkedin.com/in/kruthi-s-9787512a1/) 

