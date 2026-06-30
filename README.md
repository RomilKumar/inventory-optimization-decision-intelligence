#  Data-Driven Inventory Optimization & Decision Intelligence System

An end-to-end **Supply Chain Analytics** and **Business Intelligence** project designed to optimize inventory management using **Python, SQL, MySQL, Power BI, and Machine Learning concepts**.

The project combines data engineering, analytics, forecasting, KPI monitoring, and interactive dashboards to help businesses reduce inventory costs, prevent stockouts, and make data-driven inventory decisions.



#  Project Overview

Efficient inventory management is one of the biggest challenges for retail and manufacturing businesses. Overstocking increases warehouse and carrying costs, while understocking leads to stockouts, lost sales, and poor customer satisfaction.

This project provides a complete inventory analytics solution by integrating multiple data sources, computing business KPIs, forecasting demand, identifying operational risks, and generating actionable recommendations through an interactive Power BI dashboard.



#  Business Objectives

- Monitor inventory performance using business KPIs
- Forecast future product demand
- Identify stockout and overstock risks
- Optimize reorder decisions
- Analyze supplier performance
- Reduce inventory carrying costs
- Improve warehouse utilization
- Enhance end-to-end supply chain visibility

---

# 🛠 Tech Stack

## Programming

- Python
  - Pandas
  - NumPy
  - Matplotlib
  - Scikit-learn

## Database

- MySQL
- SQL

## Business Intelligence

- Microsoft Power BI
- Power Query
- DAX

## SQL Concepts Used

- Joins
- Aggregations
- Window Functions
- CTEs
- Subqueries

## Visualization

- KPI Cards
- Line Charts
- Bar Charts
- Donut Charts
- Matrix Tables
- Slicers
- Interactive Filters

## Version Control

- Git
- GitHub

---

#  Project Workflow

```
Raw Data
      │
      ▼
Python Data Cleaning
      │
      ▼
MySQL Database
      │
      ▼
SQL Queries
      │
      ▼
Exploratory Data Analysis
      │
      ▼
KPI Computation
      │
      ▼
Demand Forecasting
      │
      ▼
Recommendation Engine
      │
      ▼
Power BI Dashboard
      │
      ▼
Business Decision Making
```

---

#  Dataset

The project includes multiple datasets representing different aspects of inventory management.

### Products

- Product ID
- Product Name
- Category
- Brand
- Cost Price
- Selling Price

### Inventory

- Inventory ID
- Product ID
- Warehouse ID
- Stock Quantity
- Reorder Level
- Safety Stock

### Sales

- Sale ID
- Product ID
- Quantity Sold
- Sale Date
- Revenue

### Suppliers

- Supplier ID
- Supplier Name
- Product ID
- Lead Time
- Supplier Rating

### Orders

- Order ID
- Product ID
- Order Date
- Quantity Ordered
- Quantity Delivered
- Expected Delivery Date
- Actual Delivery Date
- Delivery Status

### Warehouses

- Warehouse ID
- Warehouse Location
- Storage Capacity

---

#  Python Implementation

Python was used for data preprocessing, analysis, and forecasting.

### Tasks Performed

- Data Cleaning
- Missing Value Handling
- Duplicate Removal
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Demand Forecasting
- Recommendation Logic

Libraries Used

- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

# 🗄 SQL Implementation

The cleaned datasets were imported into MySQL for structured analysis.

### SQL Operations

- Database Creation
- Table Creation
- Data Import
- Joins
- Aggregations
- Group By
- Window Functions
- CTEs
- Business Analysis Queries

---

#  Power BI Dashboard

The dashboard provides real-time insights into inventory performance.

### KPIs

- Stock Turnover Ratio
- Inventory Utilization Rate
- Days Inventory Outstanding (DIO)
- Warehouse Utilization %
- Stockout Rate
- Overstock Ratio
- Reorder Delay Rate
- Supplier Delay Frequency
- Holding Cost
- Carrying Cost %
- Lost Sales Cost
- Forecast Accuracy
- Demand Variability Index
- Service Level %
- Fill Rate %
- Average Supplier Lead Time
- Revenue per Product
- Gross Profit Margin
- Category-wise Profitability

---

#  Recommendation Engine

Business rules automatically generate recommendations such as:

- Low Stock + High Demand → Reorder Immediately
- High Stock + Low Demand → Reduce Inventory
- Dead Stock → Apply Discounts
- Supplier Delay → Increase Safety Stock
- Low Supplier Rating → Evaluate Alternate Supplier

---

#  Business Scenarios

- Demand Spike Analysis
- Seasonal Inventory Planning
- Overstock Detection
- Stockout Prediction
- Supplier Delay Analysis
- Dead Inventory Identification

---

#  Business Impact

The project helps organizations:

- Reduce stock-related losses
- Improve inventory turnover
- Lower carrying costs
- Increase forecast accuracy
- Improve warehouse utilization
- Optimize supplier performance
- Enhance operational efficiency
- Support data-driven decision making

---

#  Repository Structure

```
Inventory-Optimization-System/
│
├── Dashboard/
│   ├── Inventory_Dashboard.png
│
├── SQL/
│   ├── create_tables.sql
│   ├── import_data.sql
│   ├── analysis_queries.sql
│
├── Python/
│   ├── data_cleaning.ipynb
│   ├── demand_forecasting.ipynb
│   ├── recommendation_engine.py
│
├── Dataset/
│   ├── Products.csv
│   ├── Inventory.csv
│   ├── Sales.csv
│   ├── Suppliers.csv
│   ├── Orders.csv
│   ├── Warehouses.csv
│
├── inventory_project.pbix
├── README.md
└── LICENSE
```

---

#  Skills Demonstrated

- Supply Chain Analytics
- Inventory Optimization
- Python
- Pandas
- NumPy
- SQL
- MySQL
- Power Query
- DAX
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Modeling
- Demand Forecasting
- Business Intelligence
- KPI Development
- Dashboard Design
- Recommendation Systems
- Data Visualization
- Git
- GitHub

---

#  Future Enhancements

- Machine Learning-based Demand Forecasting
- EOQ (Economic Order Quantity) Optimization
- ABC Inventory Classification
- Real-Time Inventory Monitoring
- Automated ETL Pipeline
- Supplier Risk Prediction
- Inventory Cost Optimization using AI

---





#  Author

Romil Kumar
Computer Science Engineering Student | Data Analytics Enthusiast

### Connect with Me

- GitHub: https://github.com/RomilKumar
- LinkedIn: https://www.linkedin.com/in/romil-kumar-842a55282/
- Email: romilkumar13@gmail.com

---

⭐ If you found this project useful, consider giving it a star!
