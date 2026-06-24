# 📊 Sales, Products & Returns Dashboard
### Power BI Report — Yalamarthi Nuthana Sree

---

## 📌 Project Overview

This Power BI report provides an end-to-end business intelligence solution covering **Sales performance**, **Product analysis**, and **Returns tracking**. It is designed to help stakeholders quickly identify trends, monitor KPIs, and make data-driven decisions across three core business areas.

---

## 📁 File

| File | Description |
|------|-------------|
| `Yalamarthi_Nuthana_Sree.pbix` | Power BI Desktop report file |

---

## 📄 Report Pages

### 1. 🛒 Sales
Provides a comprehensive view of sales performance across time, geography, and customer segments.

**Visuals included:**
- **Total Sales KPI Card** — highlights the overall sales amount at a glance
- **Line & Clustered Column Combo Chart** — compares sales amount and discount (%) over time (Year/Month)
- **Line Chart** — tracks trends in unit price and sales over time
- **Filled Map** — visualizes sales distribution across states/regions
- **Key Drivers Visual** — identifies the key factors driving sales performance
- **Slicers** — filter by Customer Segment, Year, and Month for dynamic exploration

**Key Fields:** `Sales Amount`, `Discount (%)`, `Unit Price`, `Region`, `State`, `Segment`, `Order Date`

---

### 2. 📦 Products
Focuses on product-level performance, inventory, and category-wise breakdown.

**Visuals included:**
- **Column Chart** — quantity sold by product category
- **Clustered Column Chart** — titled *"Return Reason"*, showing returns per category
- **Stacked Area Chart** — titled *"Return by Reason"*, showing return count trends by reason and product
- **Treemap** — breakdown of products by category and supplier
- **KPI** — tracks ship lag (days) against targets
- **Slicers** — filter by Product Name, Category, and Customer Segment
- **Action Button** — enables navigation between report pages

**Key Fields:** `Product Name`, `Category`, `Supplier`, `Stock Available`, `Unit Price`, `Quantity`, `Ship Lag (Days)`

---

### 3. 🔄 Returns
Analyzes return patterns to uncover problem areas by supplier, category, and reason.

**Visuals included:**
- **Donut Chart** — *"Returns by Reason"* — proportion of returns by return reason
- **Pie Chart** — *"Returns by Supplier"* — return volume broken down by supplier
- **Ribbon Chart** — *"Returns by Category"* — category-wise return counts over time
- **KPI** — *"Return Status by Supplier"* — tracks return status counts per supplier
- **Slicers** — filter by Category, Region, and Return Reason

**Key Fields:** `Return ID`, `Return Reason`, `Return Status`, `Order ID`, `Category`, `Supplier`, `Region`

---

## 🗄️ Data Model

The report is built on a relational data model with the following core tables:

| Table | Description |
|-------|-------------|
| `Orders` | Order-level transactional data — sales amount, discount, quantity, dates, region, segment |
| `Products` | Product catalog — name, category, supplier, unit price, stock |
| `Returns` | Returns records — return ID, reason, status, linked to orders |
| `Customers` | Customer details — segment and region |

---

## ✨ Key Features

- **Interactive Slicers** on every page for dynamic filtering by time, region, category, and segment
- **Cross-page navigation** using action buttons
- **Key Influencers visual** to surface the top drivers of sales
- **Map visualization** for geographic sales distribution
- **KPI tracking** for return status and shipping performance
- **Beginner friendly** 

---

## 🛠️ Tools Used

- **Microsoft Power BI Desktop**
- Data modeling with relationships across Orders, Products, Returns, and Customers tables
- Worked without DAX 

---

## 🚀 How to Use

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
2. Clone or download this repository.
3. Open `Yalamarthi_Nuthana_Sree.pbix` in Power BI Desktop.
4. Use the slicers and filters on each page to explore the data interactively.

---

## 👩‍💻 Author

**Yalamarthi Nuthana Sree**  
Feel free to connect or reach out for any questions about this project.

---
