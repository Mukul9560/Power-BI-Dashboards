# Power BI Dashboard 📊

## 📌 Project Overview

This project focuses on analyzing e-commerce sales performance, profitability, customer behavior, order status, customer satisfaction, and marketing channel performance using **Microsoft Power BI**.

The dashboard is built using a dataset containing approximately **138,116 records and 46 columns**. It transforms raw sales and customer data into interactive visualizations and business performance indicators to support data-driven decision-making.

## 🎯 Project Objectives

- Monitor overall sales and profitability.
- Analyze sales trends over time.
- Compare profit across sales channels.
- Identify customer segments contributing the most sales.
- Understand order status distribution.
- Analyze customer ratings by review sentiment.
- Evaluate sales performance across marketing channels.

## 🛠️ Tools & Technologies

- **Microsoft Power BI** — Dashboard development and visualization
- **Power Query** — Data import and transformation
- **DAX** — Measures and calculations
- **CSV** — Source data format

## 📊 Key Performance Indicators

The dashboard includes the following KPIs:

| KPI | Purpose |
|---|---|
| Total Net Sales | Measures recorded net sales |
| Total Profit | Measures recorded profit |
| Total Orders | Counts distinct orders |
| Average Order Value | Net sales divided by distinct orders |
| Total Customers | Counts distinct customers |

## 📉 Dashboard Visualizations

| Visualization | Business Purpose |
|---|---|
| Monthly Net Sales Trend | Understand how sales change over time |
| Profit by Sales Channel | Compare recorded profit across channels |
| Net Sales by Customer Segment | Identify high-contributing customer segments |
| Order Status Distribution | Understand the distribution of order statuses |
| Average Rating by Review Sentiment | Compare average customer ratings by sentiment |
| Net Sales by Marketing Channel | Compare recorded sales across marketing channels |

## 🔍 Key Observations

- The Consumer segment contributes the highest recorded net sales among the customer segments displayed.
- Mobile App and Website show the highest recorded profit among the sales channels displayed.
- Average customer ratings differ across review sentiment categories.
- The monthly sales chart shows recurring peaks across the observed years.

These are descriptive observations from the dashboard; further validation is needed before making causal or financial conclusions.

## 🧹 Data Preparation

The data preparation process included:

- Importing the CSV dataset into Power BI.
- Reviewing and assigning appropriate column data types.
- Creating DAX measures for sales, profit, orders, customers, and average order value.
- Creating a Year-Month field for monthly trend analysis.
- Designing and formatting KPI cards, charts, and visual labels.

## ⚠️ Data Considerations

- The dataset contains multiple currency codes. Combined sales and profit totals should not be interpreted as a single comparable monetary amount until currency conversion is verified.
- Financial measures and order-status calculations should be validated before use in business decisions.
- Customer-level or other sensitive data should not be published without appropriate authorization.

## 🚀 How to Use

1. Clone or download this repository.
2. Open the `.pbix` report using Microsoft Power BI Desktop.
3. If prompted, update the source CSV file path.
4. Refresh the data if the source file is available and accessible.
5. Explore the KPI cards, trends, and analytical visuals.

## 🔮 Future Enhancements

- Validate currency conversion and financial calculations.
- Add delivery performance and returns analysis.
- Develop repeat-purchase and customer retention metrics.
- Add campaign cost and marketing ROI analysis if suitable cost data is available.
- Document validated business recommendations.

## 👨‍💻 Author

**Mukul Saini**

Aspiring Data Analyst | Power BI | SQL | Python | Excel

---

*This project demonstrates the use of business intelligence techniques to explore e-commerce performance and communicate findings through interactive visualizations.*
