# 📊 Madhav E-Commerce Sales Dashboard

An interactive Power BI dashboard built to help **Madhav Store** track and analyze their online sales performance across India. The dashboard enables data-driven decision-making through drill-down capabilities, dynamic filters, and a rich variety of visualizations.

---

## 📌 Key Metrics

| Metric | Value |
|---|---|
| 💰 Sum of Amount | 438K |
| 📦 Sum of Quantity | 6K |
| 📈 Sum of Profit | 37K |
| 🛒 Sum of AOV | 121K |

---

## 🎯 Project Learnings

- **Interactive Dashboard** — Created an interactive dashboard to track and analyze online sales data across states, categories, customers, and time periods.
- **Drill-Down & Filtering** — Used complex parameters to drill down in worksheets and customized views using filters and slicers (quarter-wise and state-wise).
- **Data Modeling** — Created connections, joined new tables, and built DAX calculations to manipulate data and enable user-driven parameters for visualizations.
- **Diverse Visualizations** — Used different types of customized visualizations including bar charts, pie charts, donut charts, clustered bar charts, scatter charts, line charts, area charts, maps, and slicers.

---

## 📁 Dataset

The project uses two CSV files:

```
Madhav-Ecommerce-Dashboard/
├── Orders.csv       ← Order-level data (order ID, date, customer name, state, city, amount)
├── Details.csv      ← Line-item data (category, sub-category, quantity, profit, payment mode)
├── Dashboard.pbix   ← Power BI report file
└── README.md
```

---

## 📊 Visualizations Included

| Chart Type | Insight |
|---|---|
| Stacked Bar Chart | Top states by sales amount |
| Donut Chart | Quantity by product category |
| Donut Chart | Quantity by payment mode |
| Column Chart | Monthly profit-loss trend |
| Horizontal Bar Chart | Profit by sub-category |
| Bar Chart | Top customers by order value |
| KPI Cards | Summary tiles (Amount, Quantity, Profit, AOV) |
| Slicers | Quarter-wise & state-wise filters |

---

## 🔍 Key Insights

- 🏆 **Maharashtra** leads all states in total sales, followed by Madhya Pradesh.
- 👕 **Clothing** dominates at **63%** of total quantity sold; Electronics at 21%, Furniture at 17%.
- 💵 **Cash on Delivery (COD)** is the most preferred payment mode at **44%**.
- 🖨️ **Printers** and **Bookcases** are the highest-profit sub-categories.
- 📉 Losses were recorded during **June–September**; strong recovery seen in **November**.

---

## 📸 Dashboard Preview

https://github.com/Srishh-ti/E-commerce-Sales-Dashboard/blob/main/dashboard_preview.png

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Dashboard creation and data modeling
- **Microsoft Excel / CSV** — Data source files
- **DAX** — Custom calculations and measures
- **Power Query** — Data transformation and joining tables

---

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone [https://github.com/Srishh-ti/E-commerce-Sales-Dashboard]
   ```
2. Open `Dashboard.pbix` in **Power BI Desktop**.
3. If prompted, update the data source path to point to your local `Orders.csv` and `Details.csv` files.
4. Refresh the data and explore the dashboard using quarter and state filters.

---

⭐ If you found this project helpful, please give it a star!
