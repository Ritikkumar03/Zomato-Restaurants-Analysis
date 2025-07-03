# Zomato Restaurant Data Analysis Project

## 📊 Project Overview

This project focuses on analyzing Zomato restaurant data using **Microsoft Excel** and **Power BI** to uncover trends, behaviors, and insights from the restaurant industry across various countries and cities.

The goal was to transform raw data into meaningful, interactive visuals and reports that can help in strategic decision-making and understanding business dynamics in the food service sector.

---

## 🧰 Tools Used

- **Microsoft Excel**: Data cleaning, transformation, and initial exploration  
- **Power BI**: Data modeling and interactive dashboard development  

---

## 🔍 Key Objectives

- Build a dynamic **country map table**
- Create a detailed **calendar table** using `DateKey`, enriched with:
  - `Year`, `Month Number`, `Month Name`, `Quarter`
  - `Year-Month` format (e.g., 2025-Jul)
  - `Weekday Number`, `Weekday Name`
  - `Financial Month` (April = FM1 to March = FM12)
  - `Financial Quarter`
- Analyze:
  - Number of restaurants by **country** and **city**
  - **Opening trends** by year, quarter, and month
  - **Restaurant distribution** by average rating
  - **Price range buckets** and count per bucket
  - Percentage of restaurants offering:
    - **Table Booking**
    - **Online Delivery**
  - Cuisine patterns and their geographic trends

---

## 📈 Excel Highlights

- **Functions Used**:  
  `SUMIFS`, `COUNTIFS`, `VLOOKUP`, `INDEX-MATCH`, `YEAR`, `MONTH`, `TEXT`
- **Data Manipulation**:  
  - Created PivotTables and PivotCharts for summary views
  - Applied Conditional Formatting to highlight trends
  - Used Report Connections to link multiple PivotTables via slicers

---

## 📊 Power BI Dashboard Features

- **Data Modeling** with relationships and calculated columns
- Custom **DAX Measures** for metrics such as:
  - % of restaurants with online delivery
  - Ratings-based segmentation
- **Interactive Visuals**:
  - Charts and Maps
  - Slicers for dynamic filtering
  - Drill-throughs for detailed exploration

---

## 📁 Project Files

- `Zomato_Restaurant_Data.xlsx` – Raw + processed data tables
- `Zomato_Analysis_Dashboard.pbix` – Power BI interactive report

---

## 🚀 How to Use

1. Open the Excel file to view raw data and initial PivotTable explorations.
2. Launch the Power BI `.pbix` file to interact with the full dashboard and visualizations.

---

## 📌 Future Scope

- Add deeper regional comparisons
- Incorporate sentiment data from customer reviews (if available)
- Extend the analysis to delivery trends, cost dynamics, and operational KPIs



