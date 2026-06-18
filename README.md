# 📊 Adventure Works Business Performance Dashboard

## 📌 Project Overview
An interactive Power BI dashboard designed to analyze sales performance, track regional trends, and uncover product profitability metrics for the Adventure Works dataset.

## 🛠️ Tools & Technologies Used
* **Power BI Desktop** – Data modeling, DAX engineering, and dashboard design.
* **Power Query** – Data cleaning, profiling, and transforming raw tables.
* **Star Schema** – Modeled relationships between sales facts and dimension tables.

## 🧮 Advanced DAX Calculations
*Example of a key metric engineered for this dashboard:*
* **Year-over-Year Sales:** `YoY_Sales = CALCULATE(SUM(Sales[SalesAmount]), SAMEPERIODLASTYEAR('Calendar'[Date]))`

## 💡 Key Business Insights Discovered
* *Most ordered Product is Tires and Tubes and Most returned Product is Shorts*
