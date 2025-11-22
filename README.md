# powerbi-ecommerce-sales-dashboard

A complete Power BI project analyzing revenue trends, customer performance, product contribution, supplier strength, and regional distribution. The dashboard helps business owners understand what drives sales and where improvement opportunities exist.

---

## Project Overview

This project contains a two-page Power BI report and an additional Insights section. It presents a clear breakdown of yearly performance, monthly trends, customer activity, product strength, and divisional sales.  
The goal is simple: **Turn raw sales data into actionable insights.**

---

## Tools & Skills Used
- Power BI Desktop  
- Data Modeling (Star Schema)  
- Power Query (Data Cleaning)  
- DAX Calculations  
- Interactive Visuals  

---

## Dataset Description

The dataset contains multi-dimensional e-commerce sales records made up of several related tables:

- **Sales Transactions:** quantity, revenue, unit price, transaction keys  
- **Customer Information:** name, customer key, contact details  
- **Product Details:** item name, category, supplier, manufacturer country  
- **Store Information:** division, district, store location  
- **Payment & Transaction Type:** payment method, bank, transaction type  
- **Calendar Table:** date, month, quarter, week, year  

This structure supports time intelligence, product analysis, customer segmentation, and regional insights.

---

## Data Model

A clean and simple star schema was used:

- **Fact Table:** Sales  
- **Dimension Tables:** Customer, Item, Store, Transaction Type, Calendar  

This structure improves filtering, performance, and analytical flexibility.

---

## Dashboard 1 — Business Performance Overview

This dashboard provides a high-level summary of company performance.

**Visuals included:**
- Total Revenue  
- Total Quantity Sold  
- Average Unit Price  
- YoY Indicators  
- Monthly Sales Trend  
- Customer KPI  
- Top 5 Customers  
- Top 5 Units Sold  
- Global Sales Distribution Map  

---

## Dashboard 2 — Product, Supplier & Regional Analysis

Focused on deeper operational performance.

**Visuals included:**
- Transaction Type Breakdown  
- Top Selling Products  
- Supplier Contribution  
- Divisional (Regional) Sales  
- Item Performance  

---

## Key Insights

- **Monthly Sales Trend:** Revenue stays between **$8M and $9.1M** all year.  
  **January, May, and July** recorded the highest sales;  **February** had the lowest.  
- Total revenue passed **$105M**, showing strong annual performance.  
- Quantity sold shows consistent YoY growth — demand is rising.  
- A small group of customers drives a large share of revenue.  
- Top-performing regions: **Bangladesh, India, Lithuania, Poland, Germany**.  
- Best-selling categories: **Kitchen Supplies, Sweets, Mints, Snacks, and Medicine**.  
- Key suppliers: **DENIMAC Ltd**, **INDO COUNT INDUSTRIES Ltd**, **BIGSO AB**, **CHROMADURLIN S.A.S**.  

---

## Recommendations

- Strengthen relationships with top suppliers.  
- Increase inventory for high-demand categories.  
- Investigate weak regions for growth opportunities.  
- Review pricing strategy since unit prices remain stable.  
- Promote incentives for less-used payment methods.  

---


## Dashboard 

![Screenshot (341)](https://github.com/user-attachments/assets/e665e606-758a-49c0-8bb1-cfa59ac7f8ba)
![Screenshot (342)](https://github.com/user-attachments/assets/861e9b22-51df-4cbf-8fc8-e30c3953802f)
![Screenshot (343)](https://github.com/user-attachments/assets/f0c91e9e-de3c-4cc0-be48-d7a0cf54e78b)

## How to Use

1. Download the `.pbix` file from this repository.  
2. Open in Power BI Desktop.  
3. Explore the dashboards, data model, and DAX measures.  
4. Interact with visuals to view insights.  
