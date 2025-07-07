# Power BI Sales & Leads Visualization Project

📊 A practice project focusing on building rich, interactive visualizations in **Power BI** using **Sales** and **Leads** data. The dashboard demonstrates various chart types to highlight business insights, sales performance, and lead behavior.

---

## 📌 Project Goals

- Develop a visually intuitive and interactive Power BI dashboard
- Apply a variety of charts to represent different business metrics
- Gain insights into sales, profit trends, customer segments, and regional performance

---

## 📊 Visuals Included

| Chart Type | X-Axis | Y-Axis | Additional Info |
|------------|--------|--------|------------------|
| **Bar Chart** | City | Sum of Sale | Displays total sales across cities |
| **Column Chart** | Segment | Sum of Sale | Compares sales across customer segments |
| **Pie Chart / Donut Chart** | Segment | Sum of Sale | Shows the share of each segment in total sales |
| **Clustered Column Chart** | Category | Sum of Sale | Compares sales among product categories |
| **Line Chart** | Ship Mode | Profit | Profit trend by shipping method |
| **Area Chart** | Ship Mode | Sum of Quantity | Quantity sold by shipping method |
| **Line & Stacked Column Chart** | Order Date | Sales (Column), Profit (Line) | Monthly sales + profit comparison |
| **Line & Clustered Column Chart** | Order Date | Sales (Column), Quantity (Line) | Trend of sales and quantities over time |
| **Map** | City | — | Shows geographic distribution of sales or orders |
| **Funnel Chart** | Type | Sum of Count | Lead/sales funnel based on stages or types |
| **Gauge Chart** | — | Sum of Profit | Target: Min and Max values used as thresholds |
| **KPI Card** | — | Sum of Profit | Trend: Order Date; Target-based performance tracking |
| **Decomposition Tree** | Category → Sub-Category | Sum of Profit | Allows drill-down by category and sub-category |

---

## 📷 Dashboard Preview
![Gauge](https://github.com/user-attachments/assets/5efce5ca-a5a6-4cba-9031-832f3bea7e9c)


---

## 🔗 Live Dashboard

👉 [Click here to view the Power BI Dashboard]([https://app.powerbi.com/view?r=EXAMPLE_LINK_ID](https://app.powerbi.com/view?r=eyJrIjoiNTY3MThlOWQtOWZjZC00NjRiLTlkMmItYTk5YjYyN2VmYzkwIiwidCI6IjZkNjAwMTM4LTA5MzItNDliZC05NTFjLTBkODM4MmIxZWU3NCJ9&pageName=e42ba82308257c564ca1))

> This report shows various visualizations of Sales and Leads data including KPIs, funnel, maps, profit trends, and more.


---

## ⚙️ How to Use

1. Clone this repository or download the files
2. Open `All_Viz.pbix` in **Power BI Desktop**
3. Load the data from `data/` folder
4. Interact with the visuals and apply filters/slicers as needed
5. Optional: Customize visuals or connect to your own dataset

---

## 🛠 Tools Used

- Power BI Desktop
- DAX (Calculated columns, KPIs)
- Custom visuals: KPI, Decomposition Tree, Funnel, Gauge
- Sample data in CSV format

---

## 🧠 Sample Insights

- Major sales are concentrated in a few metro cities
- Corporate segment shows higher average order values
- Most orders are shipped via "Standard Class" but yield lower profit
- Funnel shows lead drop-offs between initial contact and final conversion
- Highest contribution to profit is from "Technology" → "Phones"

---

## 🔗 Publish or Share

You can publish this report to [Power BI Service](https://app.powerbi.com/) and use the **"Publish to Web"** link in your LinkedIn, GitHub profile, or portfolio.

---

## 📄 License

This project is for educational and portfolio use. Feel free to fork and adapt it.

---
