# PowerBI-MySQL-Customer-Dashboard
## 📌 Project Overview
This project demonstrates how to build an interactive Customer Dashboard using MySQL and Power BI.

The data is stored in a MySQL database and visualized in Power BI using multiple charts, cards, slicers, and relationships.
## Technologies Used
- Power BI
- MySQL
- SQL
# 📂 Database Details
### Database Name`cus`

### Tables
#### cus1 (Customer Table)
- customer_id
- customer_name
- city
- age
- mobile
Contains 50 customer records.
#### cus2 (Orders Table)
- order_id
- customer_id
- product_name
- quantity
- amount
- order_date
Contains 50 order records.
Relationship:
cus1.customer_id
        │
        │ 1 ─────────── *
        │
cus2.customer_id

## 📊 Dashboard Features

- Customer Analysis
- Sales Analysis
- City-wise Customer Distribution
- Product-wise Sales
- Interactive Slicers
- Data Relationship
## 📈 Visualizations Used
- Card
- Pie Chart
- Doughnut Chart
- Bar Chart
- Table
- Slicer
## 📁 Project Files
- Customer_Dashboard.pbix
- customer.sql
- Dashboard.png
- README.md
