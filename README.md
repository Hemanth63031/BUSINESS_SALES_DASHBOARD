# Business Sales Analytics Dashboard | SQL Server | Power BI | DAX | E-Commerce Dataset


This project involves the development of an **interactive Business Sales Analytics Dashboard** for an e-commerce business scenario using **SQL Server and Power BI**.

The dashboard provides comprehensive insights into **sales performance, profitability, product trends, regional sales distribution, and customer segment analysis**. It enables stakeholders to track **Year-To-Date (YTD) performance**, identify **top and bottom performing products**, and make **data-driven business decisions**.

---

# 📊 Dashboard Preview

![image alt](https://github.com/Hemanth63031/BUSINESS_SALES_DASHBOARD/blob/main/powerbidashboard.png?raw=true)

---

# 🔄 End-to-End Data Pipeline

This project demonstrates a **complete data analytics workflow** from data extraction to business insights.

### 1️⃣ Data Collection

* Extracted structured **E-commerce sales data from SQL Server**
* Imported required tables into **Power BI**

### 2️⃣ Data Preparation

* Removed duplicate records
* Handled missing values
* Standardized **product categories and customer segments**

### 3️⃣ Data Modeling

* Implemented a **Star Schema data model**
* Created relationships between **fact and dimension tables**
* Optimized the model for **better query performance**

### 4️⃣ KPI Development

Developed important business KPIs such as:

* **Total Sales**
* **Total Profit**
* **Total Quantity**
* **Profit Margin**
* **Year-To-Date (YTD) Sales**
* **Year-Over-Year (YoY) Growth**

### 5️⃣ Dashboard Visualization

Designed an **interactive Power BI dashboard** including:

* KPI Cards
* Regional map analysis
* Category performance charts
* Product ranking visuals
* Customer segment filtering

---

# 📐 Key DAX Measures

Below are some of the important DAX measures used in this project.

```
Total Sales =
SUM(Sales[Sales Amount])

Total Profit =
SUM(Sales[Profit])

Total Quantity =
SUM(Sales[Quantity])

Profit Margin =
DIVIDE([Total Profit], [Total Sales], 0)

YTD Sales =
TOTALYTD([Total Sales], 'Calendar'[Date])

PYTD Sales =
CALCULATE([Total Sales], SAMEPERIODLASTYEAR('Calendar'[Date]))

YoY Growth =
DIVIDE([YTD Sales] - [PYTD Sales], [PYTD Sales])
```

---

# 📊 Key Business Questions Solved

A **US-based e-commerce company** requested a sales dashboard to track **Year-To-Date performance and business insights**.

The dashboard answers the following business questions:

### 1️⃣ KPI Performance

Create a KPI banner displaying:

* **YTD Sales**
* **YTD Profit**
* **YTD Quantity Sold**
* **YTD Profit Margin**

---

### 2️⃣ Year-Over-Year Growth Analysis

Calculate **Year-Over-Year (YoY) growth for each KPI** and display **YTD sparklines** to understand monthly trends.

---

### 3️⃣ Category Performance Analysis

Analyze **YTD Sales, PYTD Sales, and YoY Sales growth** for different product categories.

Categories include:

* Furniture
* Technology
* Office Supplies

Trend indicators are added to highlight **performance changes**.

---

### 4️⃣ State-Level Sales Analysis

Visualize **YTD Sales by US State** using a geographic map to identify high-performing markets.

---

### 5️⃣ Product Performance

Identify **Top 5 and Bottom 5 products** based on sales performance.

---

### 6️⃣ Regional Sales Analysis

Analyze **YTD Sales by Region** to identify the **best and worst performing regions across the country**.

---

### 7️⃣ Shipping Performance

Analyze **YTD Sales by Shipping Type** to identify the most efficient shipping methods.

---

# 🧠 Analytical Insights

Key insights derived from the dashboard include:

* **Technology category generates the highest revenue contribution**
* **Office Supplies show consistent demand across regions**
* **Furniture has higher sales but relatively lower profit margins**
* **Consumer segment contributes the majority of total sales**
* **Corporate segment shows higher profitability per order**

These insights help businesses focus on **high-performing products, categories, and regions**.

---

# 📈 Performance Optimization

Several techniques were implemented to improve dashboard performance:

* Optimized **Power BI data model**
* Implemented **Star Schema architecture**
* Created efficient **DAX calculations**
* Removed unnecessary columns
* Built optimized relationships between tables

### Result

⚡ Faster dashboard loading
⚡ Improved report performance
⚡ Better scalability for large datasets

---

# 💼 Real-World Business Value

This dashboard provides valuable insights for different stakeholders.

### 📊 Sales Managers

Track **product and regional sales performance**.

### 📦 Product Teams

Identify **top-performing product categories**.

### 🌎 Regional Managers

Analyze **sales distribution across states and regions**.

### 📈 Executives

Monitor **overall business performance using KPI indicators**.

---

# 🏆 Project Highlights

✔ End-to-End Data Analytics Project
✔ Real-World E-Commerce Dataset
✔ SQL Server + Power BI Integration
✔ Advanced DAX Calculations
✔ Interactive Dashboard Design
✔ Geographic Sales Visualization
✔ Customer Segment & Category Analysis

---

# 🧠 Skills Demonstrated

This project demonstrates the following **Data Analyst skills**:

* SQL Data Extraction
* Data Cleaning & Transformation
* Data Modeling (Star Schema)
* DAX Calculations
* Power BI Dashboard Development
* Business Insight Generation
* Data Visualization Best Practices

---

# 🚀 How to Use This Repository

### 1️⃣ Clone the repository

```
git clone https://github.com/yourusername/business-sales-dashboard.git
```

### 2️⃣ Open the Power BI file

```
business_sales_dashboard.pbix
```

### 3️⃣ Explore the interactive dashboard

### 4️⃣ Analyze sales insights by:

* Region
* Category
* Customer Segment

---

# 📌 Project Architecture

The Business Sales Dashboard follows a **modern analytics architecture**.

```
SQL Server Database
        │
        │  (Data Extraction using SQL Queries)
        ▼
Data Transformation Layer
        │
        │  (Data Cleaning & Modeling)
        ▼
Power BI Data Model
        │
        │  (DAX Measures & KPIs)
        ▼
Interactive Business Dashboard
        │
        ▼
Business Insights & Decision Making
```

This architecture ensures:

* Scalable data processing
* Efficient data modeling
* Fast dashboard performance
* Real-time decision support

---

# 👨‍💻 Author

**Adimulapu Hemanth Abhay**

Data Analyst | SQL | Power BI | Data Visualization

📧 [hemanthabhayadimulapu@gmail.com](mailto:hemanthabhayadimulapu@gmail.com)
📱 +91 9398436912

---
