# Blinkit Customer Retention & Cohort Analysis




Project Overview

This project analyzes customer retention behavior, cohort performance, delivery operations, and customer feedback for Blinkit using SQL and Tableau.

The project follows Medallion Architecture principles to transform raw retail datasets into structured analytical models for business intelligence and dashboard reporting.

⸻

Business Objective

The objective of this project is to:

* Analyze customer retention behavior
* Track customer cohorts over time
* Understand repeat customer patterns
* Evaluate delivery performance
* Generate operational business insights
* Build a structured analytical workflow using Medallion Architecture

⸻

Tools & Technologies

* MySQL Workbench￼
* Tableau Public￼
* SQL
* GitHub￼
* Medallion Architecture

⸻

Dataset Information

Dataset Source:

* Kaggle Blinkit Dataset￼

Datasets Used:

* Customers
* Orders
* Products
* Delivery Performance
* Customer Feedback
* Inventory
* Marketing Performance

⸻

Medallion Architecture

Bronze Layer

Raw CSV ingestion layer containing untouched source datasets.

Bronze Tables

* bronze_customers
* bronze_orders
* bronze_products
* bronze_delivery
* bronze_feedback
* bronze_inventory
* bronze_marketing

⸻

Silver Layer

Cleaned and transformed layer used for structured analytics.

Silver Tables

* silver_customers
* silver_orders
* silver_products
* silver_delivery
* silver_feedback
* silver_inventory
* silver_marketing

Data Cleaning Performed

* NULL handling
* Deduplication
* String standardization
* Data validation
* Column selection

⸻

Gold Layer

Business-ready analytical tables optimized for Tableau dashboards.

Gold Tables

* gold_customer_retention
* gold_cohort_analysis

Analytical Focus

* Customer retention
* Cohort tracking
* Customer lifecycle analysis
* Repeat customer behavior
