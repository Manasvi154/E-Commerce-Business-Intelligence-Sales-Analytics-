# E-Commerce Business Intelligence & Sales Analytics

An end-to-end Business Intelligence project built using **MySQL** and **Power BI** to analyze over **100,000 real-world e-commerce transactions**. The project demonstrates the complete analytics workflow—from SQL-based data extraction and business analysis to interactive Power BI dashboards for executive decision-making.

---

# Executive Summary

This project follows a complete data analytics lifecycle by combining SQL and Power BI.
The workflow begins with importing large CSV datasets into a MySQL relational database, designing relationships across multiple tables, and writing SQL queries to analyze customer behavior, sales performance, seller performance, and payment trends. The processed data is then modeled in Power BI using a Star Schema, where Power Query and DAX are used to create KPIs and interactive dashboards for business reporting.

### Project Highlights

- 100K+ E-commerce Records
- 6 Related Database Tables
- 25+ DAX Measures
- 5 Interactive Power BI Dashboards
- End-to-End Business Intelligence Workflow

---

# Business Problem

E-commerce companies generate large volumes of transactional data every day. However, raw data alone does not provide actionable insights for business teams.

The objective of this project was to transform raw sales data into meaningful business intelligence by answering questions such as:

- Which product categories generate the highest revenue?
- Which states contribute the most sales?
- Which sellers drive the highest revenue?
- How do customers purchase over time?
- Which payment methods are most preferred?
- What is the average delivery time?
- Which business areas offer opportunities for operational improvement?

---

# Methodology

### Phase 1 – SQL (MySQL)

- Imported and validated 100K+ CSV records into MySQL
- Designed a relational database using Primary & Foreign Keys
- Worked with six related tables:
  - Customers
  - Orders
  - Order Items
  - Products
  - Sellers
  - Payments
- Performed business analysis using:
  - JOINs
  - GROUP BY
  - Aggregate Functions
  - CASE Statements
  - Subqueries
  - Common Table Expressions (CTEs)
  - Window Functions

### Phase 2 – Power BI

- Imported SQL data into Power BI
- Built a Star Schema data model
- Performed data transformation using Power Query
- Created 25+ DAX measures and KPIs
- Designed five interactive dashboards:
  - Executive Dashboard
  - Sales Analysis Dashboard
  - Customer Analysis Dashboard
  - Product Analysis Dashboard
  - Seller & Delivery Analysis Dashboard

---

# Dashboard Preview

### Executive Dashboard

<img width="1443" height="813" alt="Executive dashboard" src="https://github.com/user-attachments/assets/d9522307-d503-4bcd-bd5f-dc8534e03e6c" />

### Sales Analysis Dashboard

<img width="1438" height="808" alt="Sales analysis" src="https://github.com/user-attachments/assets/371d104d-a7ab-4285-996b-306765ce979d" />

### Customer Analysis Dashboard

<img width="1442" height="813" alt="Customer analysis" src="https://github.com/user-attachments/assets/6ff470fd-57cd-4efa-96a2-57c3d75902e3" />

### Product Analysis Dashboard

<img width="1442" height="808" alt="Products analysis" src="https://github.com/user-attachments/assets/31b79bfa-ad44-46b1-bad1-8f9af65cd5a9" />

### Seller & Delivery Analysis Dashboard

<img width="1441" height="812" alt="Seller Delivery analysis" src="https://github.com/user-attachments/assets/f2c08b6d-4bef-4fa0-b3e3-c2d2ae5dbe77" />

---

# Skills Demonstrated

### SQL

- Database Design
- Relational Data Modeling
- JOINs
- GROUP BY
- Aggregate Functions
- CASE Statements
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- Business Query Writing

### Power BI

- Power Query
- Data Cleaning
- Star Schema Modeling
- DAX
- KPI Development
- Interactive Dashboard Design
- Data Visualization

### Business Analytics

- Sales Analysis
- Customer Analytics
- Product Performance Analysis
- Seller Performance Analysis
- Payment Analysis
- Delivery Performance Analysis
- Executive Reporting

---

# Results & Business Recommendations

## Business Results

- Sales Revenue: **13.59M**
- Orders Processed: **99K**
- Customers: **96K**
- Products Sold: **113K+**
- Product Categories: **74**
- Average Delivery Time: **~12 Days**

## Key Insights

- Health & Beauty generated the highest product revenue.
- São Paulo (SP) contributed the largest share of overall sales.
- Credit Card was the most frequently used payment method.
- A relatively small group of sellers generated a significant portion of total revenue.
- Delivery performance varied across seller regions, highlighting opportunities to improve logistics efficiency.

---

# Next Steps

Future improvements planned for this project include:

- Deploy the dashboard using Power BI Service.
- Add Row-Level Security (RLS) for role-based reporting.
- Build a real-time dashboard using streaming data.
- Integrate Python for predictive sales forecasting.
- Automate ETL using SQL procedures or Power Automate.

