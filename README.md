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

## Dashboard Screenshots
<img width="1117" height="631" alt="Executive Dashboard" src="https://github.com/user-attachments/assets/54372997-3947-4372-8c17-00729158d55f" />
<img width="1122" height="630" alt="Map Details" src="https://github.com/user-attachments/assets/8ea7ffb4-1f67-421a-88fc-eea3ce843d0c" />
<img width="1121" height="630" alt="Product Details" src="https://github.com/user-attachments/assets/dc26f8cd-a9d7-48ab-b499-a800f8a914e6" />
<img width="1122" height="632" alt="Customer Details" src="https://github.com/user-attachments/assets/087d1a98-44ca-4247-aeb9-e63d402fefca" />
