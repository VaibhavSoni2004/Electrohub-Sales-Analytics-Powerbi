# ElectroHub Sales Analytics Dashboard

An end-to-end retail business intelligence solution built using **Microsoft Power BI**, **Power Query**, and **Data Modeling**. This project tracks performance indicators, geographic distribution, product profitability, and comparative period trends for retail operations.

---

## Dashboard Previews

### 1. Executive Sales Overview
Macro KPI metrics, geographic bubble distribution across key Indian metropolitan hubs, discount breakdowns by promotional campaigns, and chronological transaction volume trends.

![Overview](<dashboard images/Page 1 Overview.png>)

---

### 2. Product Performance & Margin Analysis
Granular breakdown of top-performing and underperforming products evaluated by revenue contribution, order quantities, and net profit margins.

![Top and Bottom Trends](<dashboard images/page 2 Top_Bottom_Trends.png>)

---

### 3. Dynamic Period-to-Period Comparison
Comparative analytical module allowing dynamic slice-and-dice evaluation of sales, units sold, and profit variations across user-selected time horizons.

![Sales Period Comparison](<dashboard images/page 3 Sales_Period_Comparison.png>)

---

### 4. Tabular Audit & Detailed Records
Filterable relational matrix view providing itemized records across transactions, categories, customer segments, and order statuses.

![Filter Table Data](<dashboard images/page 4 Filter_Table_Data.png>)

---

## Key Features & Business Insights

- **Geospatial Intelligence:** Regional footprint mapping highlighting high-traction regions (e.g., Bhopal, Indore, Nagpur, Mumbai, Bangalore) against secondary retail locations.
- **Campaign Effectiveness:** Evaluation of seasonal promotions (*Weekend Flash Sale*, *Clearance Sale*, *Summer Sale*, *New Year Special*) against gross margins.
- **Outlier & Trend Detection:** High-frequency transaction monitoring over 2020–2024 to identify volume spikes, demand surges, and inventory seasonality.
- **Dynamic Slicing:** Multi-variable parameter filtering enabling period-over-period comparative analysis.

---

## Tech Stack & Data Workflow

- **Analytics & BI:** Microsoft Power BI Desktop
- **ETL & Data Transformation:** Power Query (type casing, null handling, calculated date dimensions)
- **Data Modeling:** Star Schema design with dedicated Fact and Dimension tables
- **Formulas & Metrics:** Custom DAX measures for aggregated sales, margin ratios, and rolling period totals
