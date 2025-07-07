# Power BI Sales & Leads Visualization Project

📊 A practice project focusing on building rich, interactive visualizations in **Power BI** using **Sales** and **Leads** data. The dashboard demonstrates various chart types to highlight business insights, sales performance, and lead behavior.

---

## 📌 Project Goals

- Develop a visually intuitive and interactive Power BI dashboard
- Apply a variety of charts to represent different business metrics
- Gain insights into sales, profit trends, customer segments, and regional performance

---

---

## 📊 Visuals Included

| Chart Type | Dimensions & Measures | Description |
|------------|------------------------|-------------|
| **Bar Chart** | City, Sum of Sale | Shows sales distribution across cities |
| **Column Chart** | Segment, Sum of Sale | Compares sales by customer segments |
| **Pie Chart** / **Donut Chart** | Segment, Sum of Sale | Visual share of each segment in total sales |
| **Clustered Column Chart** | Category, Sum of Sale | Sales performance across product categories |
| **Line Chart** | Ship Mode, Profit | Trend of profit across different shipping modes |
| **Area Chart** | Ship Mode, Sum of Quantity | Total quantity sold by shipping mode |
| **Line & Stacked Column Chart** | Order Date, Sales, Profit | Combined view of monthly profit trends and sales volume |
| **Line & Clustered Column Chart** | Order Date, Sales, Quantity | Relationship between sales and quantity over time |
| **Map** | City | Geographical visualization of city-level sales |
| **Funnel Chart** | Type, Sum of Count | Lead journey stages or sales funnel representation |
| **Gauge Chart** | Sum of Profit, Max, Min | Current profit status vs target/thresholds |
| **KPI Card** | Profit, Order Date, Target-Trend | Key performance indicator tracking |
| **Decomposition Tree** | Profit, Category, Sub-category | Drill-down analysis of profit across categories |

---

## 📷 Dashboard Preview

![Dashboard Screenshot](images/dashboard_preview.png)

---

## 🧠 Key Insights (Sample)

- **Top-selling cities** drive over 40% of total revenue.
- **Consumer segment** leads in both sales and profit margin.
- **Standard Class shipping** contributes the most to overall quantity but with lower profit.
- A clear upward **sales trend** seen in Q4 with simultaneous **profit peaks**.
- Decomposition tree reveals **Office Supplies → Binders** as a profit bottleneck.

---

## ⚙️ How to Use

1. Download or clone the repository.
2. Open `sales_leads_dashboard.pbix` in **Power BI Desktop**.
3. Replace the sample data with your own if needed (use `sales_data.csv`, `leads_data.csv`).
4. Explore, interact, or modify visuals and filters.

---

## 🛠 Tools Used

- Power BI Desktop
- DAX for calculated columns/measures
- CSV files (mock sales/leads data)
- Power BI native visuals and filters

---

## 📌 Possible Enhancements

- Add slicers for dynamic filtering (e.g., region, year)
- Integrate real-time data sources (Excel, SQL)
- Create drill-through pages for segment or category-level analysis
- Publish to Power BI Service and embed it in a portfolio or blog

---

## 📄 License

This project is for learning and portfolio purposes only. Feel free to fork and modify.

---


