# 📊 Global Electronics Retailer Dashboard

> A comprehensive Power BI report delivering actionable insights across sales, products, customers, stores, and time — built on a star schema data model.

---

## 📌 Project Overview

This Power BI dashboard provides a multi-dimensional view of **sales performance** for a global electronics retailer. It enables decision-makers to monitor key business metrics including total sales, quantity sold, revenue trends, customer behavior, and geographic performance.

The report also features analysis of customers' **buying behaviors** and **basket item correlations**, giving teams clear and informative visuals to support data-driven decisions.

The dataset follows a **star schema model**, with `Fact_Sales` as the central table connected to multiple dimension tables.

---

## 🗂️ Dashboard Pages

| Page | Description |
|------|-------------|
| 🏠 **Intro Page** | Project overview, team members, and supervisor info |
| 📈 **Sales Summary** | High-level KPIs, sales by country map, delivery rate, and YoY comparisons |
| 📋 **Sales Details** | Sales/profit/cost trends by year and month, YTY waterfall chart |
| 🛒 **Basket Influencers** | Frequently bought-together products, key sales influencers, basket size analysis |
| 📦 **Products Analysis** | Sales decomposition tree, top products by profit, brand share |
| 👥 **Customer Analysis** | Demographics, age-range orders, gender breakdown, customer funnel |
| 🏪 **Stores Insights** | Top stores by sales, repeat customer funnel, physical vs. online store comparison |

---

## 📊 Key KPIs (All-Time)

| Metric | Value |
|--------|-------|
| Total Orders | 26K |
| Total Sales | $56M |
| Total Cost | $23M |
| Total Profit | $33M |
| Avg. Gross Margin Per Unit | $164 |
| Avg. Profit Margin % | 54.6% |
| Avg. Basket Value | $2,118 |
| Total Customers | 15K |
| Average Customer Age | 58 |

---

## 🔍 Key Insights

- 🏆 **Most sold product:** WWI Desktop PC2.33 X2330 Black
- 🌍 **Top country by sales:** United States ($23.76M)
- 🏬 **Top store:** Online channel ($11.4M, 5,580 orders)
- 🛍️ **High basket orders:** 8,375 (32% of total)
- 👴 **Dominant customer segment:** 60+ age group (12.1K orders)
- 📦 **Frequent product pairs:** A. Datum Advanced Digital Camera M300 Azure is commonly bought with Adventure Works TVs, desktops, and laptops
- 📉 **Sales influencer:** Mega Store size correlates with lower average sales vs. Online channel

---

## 🧩 Data Model

The dataset is structured as a **Star Schema**:

```
Fact_Sales
    ├── Dim_Product
    ├── Dim_Customer
    ├── Dim_Store
    ├── Dim_Date
    └── Dim_Location
```

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Report development & visualization
- **DAX** — Calculated measures and KPIs
- **Power Query (M)** — Data transformation and cleaning
- **Star Schema** — Data modeling approach

---

## 👥 Team Members

| # | Name |
|---|------|
| 1 | Eman Mohamed Elsaeed Elzoghby |
| 2 | Nancy Mohamed Ashraf Higazy |
| 3 | Aalaa Mohamed AlSayed Hassan |
| 4 | Somaya Algaryb Yseen |
| 5 | Mai Mohammed Mohammed Sharabi |
| 6 | Amira Said Mohamed Mohamed |

**Supervisor:** Eng. Kareem Bakli

---

## 🚀 Getting Started

1. Clone or download this repository
2. Open the `.pbix` file in **Power BI Desktop**
3. If required, update the data source connection under **Transform Data → Data Source Settings**
4. Refresh the data and explore the report pages using the navigation tabs

---

## 📁 Repository Structure

```
├── GlobalElectronicsRetailer.pbix   # Main Power BI report file
├── README.md                        # Project documentation
└── /screenshots                     # Dashboard page previews
    ├── 01_intro.png
    ├── 02_sales_summary.png
    ├── 03_sales_details.png
    ├── 04_basket_influencers.png
    ├── 05_products_analysis.png
    ├── 06_customer_analysis.png
    └── 07_stores_insights.png
```

---

## 📷 Dashboard Screenshots

### Sales Summary
<img width="1303" height="723" alt="image" src="https://github.com/user-attachments/assets/3b1a7b48-e84a-4976-82d1-ad5a2d203716" />

### Sales Details
<img width="1304" height="724" alt="image" src="https://github.com/user-attachments/assets/78540d30-9c17-4aed-9c4d-faa75862199a" />

### Basket Influencers
<img width="1302" height="724" alt="image" src="https://github.com/user-attachments/assets/b9fdee78-08c1-4a35-b05d-d46df3fa6482" />

### Products Analysis
<img width="1296" height="727" alt="image" src="https://github.com/user-attachments/assets/54c343f8-bdac-484c-a033-482420e62562" />

### Customer Analysis
<img width="1304" height="727" alt="image" src="https://github.com/user-attachments/assets/d75af169-31b0-4772-bd5c-b10dd8414be5" />

### Stores Insights
<img width="1305" height="717" alt="image" src="https://github.com/user-attachments/assets/ce97c6d4-9492-44f1-95dd-0ac1b6861fb3" />

---

*Built with ❤️ using Power BI*
