
---

## 🧹 Data Cleaning & Transformation Summary

Power Query (M) was used to clean and shape the raw Excel data:

- ✅ Removed unnecessary columns like `Customer Name`.
- ✅ Replaced inconsistent city names using a reference sheet (e.g., `Mumbai` misspelled).
- ✅ Merged `Day`, `Month`, and `Year` into a single `Date` column.
- ✅ Ensured correct data types: `Date`, `Customer Age`, `Units Sold`.
- ✅ Filtered out null/empty values and duplicate records.
- ✅ Renamed columns for clarity (e.g., `Price Per Unit` → `Unit Price`).

---

## 📊 Dashboard Overview

The dashboard includes the following visuals and KPIs:

- 📦 **Total Units Sold**
- 💰 **Total Revenue**
- 📈 **Monthly Sales Trend**
- 🔝 **Top 5 Brands by Revenue**
- 🏙️ **Sales by City**
- ⭐ **Customer Ratings Distribution**
- 💳 **Payment Method Split**
- 🎯 **Filters** by Brand, City, Year, and Payment Method

---

### 🖼️ Sample Screenshots

> Add these in your `Screenshots/` folder and reference below:

#### 📍 Full Dashboard View  
![Dashboard Overview](Screenshots/dashboard_overview.png)

#### 📌 KPI Cards Section  
![KPI Cards](Screenshots/kpi_cards_view.png)

#### 🔧 Power Query Transformations  
![Query Steps](Screenshots/power_query_steps.png)

---

## 📈 Key Business Insights

- 🔺 **Xiaomi** has the highest unit sales but operates at a lower price point.
- 🏆 **OnePlus and Apple** dominate in revenue per unit sold.
- 🏙️ **Mumbai and Delhi** lead in mobile purchases.
- 💳 **Credit Card** and **UPI** are the top payment methods.
- ⭐ Majority of customers rate their purchases 4 or 5 stars.

---

## 🛠 Tools Used

- **Power BI Desktop**
- **Power Query Editor**
- **DAX (Data Analysis Expressions)**
- **Excel (source file)**

---

## 🎥 Tutorial Inspiration

This project style was inspired by:  
▶️ [Power BI Dashboard End-to-End Project (YouTube)](https://www.youtube.com/watch?v=ASCnLj8XHww)

---

## 🚀 How to Explore This Project

1. Download `DashBoard Project 2.pbix`.
2. Open in Power BI Desktop (free tool).
3. Explore the queries via **Transform Data** → **Advanced Editor**.
4. Interact with the visuals and slicers to explore insights.

---

## 📄 License

This project is licensed under the MIT License — free to use and modify with credit.

---
