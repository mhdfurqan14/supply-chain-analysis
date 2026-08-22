# Supply Chain Analysis

## 📌 Project Overview

This project analyzes supply chain data to identify key business insights related to
product sales, revenue, pricing, supplier performance, manufacturing, and logistics.

The analysis was conducted using Python for data cleaning, exploratory data analysis (EDA),
and business insight generation.

---

## 🎯 Business Questions

This project aims to answer the following questions:

- Which product category generates the highest revenue?
- Which products are sold the most?
- Which products have the highest and lowest prices?
- Which product category contributes the most to sales?
- Which suppliers have the best manufacturing performance?
- What is the average manufacturing lead time?
- What is the defect rate by supplier?
- How does shipping performance vary across suppliers?
- What factors may affect supply chain performance?

---

## 🗂️ Dataset

The dataset contains information related to:

- Product Type
- Price
- Revenue
- Supplier
- Manufacturing Lead Time
- Shipping Time
- Shipping Cost
- Defect Rate
- Stock Levels
- Order Quantities
- Transportation
- Location
- Other supply chain-related attributes

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Google Colab
- Power BI *(Dashboard)*

---

## 🔎 Analysis Process

### 1. Data Cleaning
- Checked missing values
- Checked duplicate records
- Checked data types
- Handled inconsistent values
- Checked potential outliers

### 2. Exploratory Data Analysis (EDA)

Analyzed:

- Product performance
- Revenue
- Pricing
- Supplier performance
- Manufacturing lead time
- Shipping performance
- Defect rate
- Inventory and stock levels

### 3. Business Insights

The analysis identified several important findings regarding:

- Revenue contribution by product category
- Product sales performance
- Pricing differences
- Supplier performance
- Manufacturing efficiency
- Supply chain quality

### 4. Dashboard

The cleaned data and analysis results were further developed into an interactive
Power BI dashboard.

---

## 📊 Key Business Insights

Some of the key findings from the analysis include:

1. Inventory Level Does Not Directly Drive Sales
The analysis shows no clear relationship between stock levels and sales volume. Higher inventory does not necessarily result in higher sales.
2. Best-Selling Products Do Not Always Have High Inventory Levels
Some of the best-selling products have relatively lower stock levels, while products with high inventory levels may have relatively low sales. This indicates that inventory allocation is not necessarily aligned with customer demand.

3. High Inventory Does Not Guarantee Strong Product Performance
Products with large stock quantities are not necessarily the products with the highest sales. This suggests a potential inventory optimization opportunity, particularly for slow-moving products.
---

## 📈 Dashboard

The Power BI dashboard provides an interactive view of:

- Total Revenue
- Total Orders
- Product Performance
- Revenue by Product Type
- Supplier Performance
- Shipping Performance

---

## 📁 Project Structure

```text
Supply-Chain-Analysis/
│
├── data/
│   └── supply_chain_data.csv
│
├── notebooks/
│   └── supply_chain_analysis.ipynb
│
├── dashboard/
│   └── supply_chain_dashboard.pbix
│
├── images/
│   └── dashboard.png
│
└── README.md
