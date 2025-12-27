# Sales, Customer & Product Performance Analysis using SQL

## Project Overview

This project demonstrates an end-to-end **business** analytics workflow using SQL to analyze sales transactions, customer behavior, and product performance. It replicates real-world Business Analyst and Data Analyst use cases, including trend analysis, segmentation, performance benchmarking, and executive-level reporting.

Using advanced SQL techniques such as CTEs, window functions, aggregations, and joins, the project transforms raw transactional data into meaningful KPIs and structured analytical reports that support data-driven decision-making.

---

## Business Objectives

- Understand sales performance trends over time  
- Identify top and underperforming products and categories  
- Segment customers based on spending and lifecycle behavior  
- Build reusable SQL reporting views for business stakeholders  

---

## Dataset Files

- `gold.fact_sales.csv` → Fact table with sales transactions (order_id, customer_id, product_id, order_date, quantity, revenue, etc.)
- `gold.dim_customers.csv` → Customer dimension with customer attributes and behavior fields.
- `gold.dim_products.csv` → Product dimension with product details, categories, and pricing-related fields.


## Tools & Technologies

- SQL (SQL Server)  
- Window Functions (SUM, AVG, LAG, RANK)  
- CTEs (Common Table Expressions)  
- Aggregations & Date Functions  
- Analytical Views for Reporting  

---

## Key Analyses Performed

1. **Change Over Time Analysis**
   - Monthly and yearly sales trends  
   - Customer growth and revenue patterns  

2. **Cumulative & Performance Analysis**
   - Running totals and averages  
   - Year-over-year product performance comparison  

3. **Segmentation & Contribution Analysis**
   - Customer segmentation (VIP, Regular, New)  
   - Product cost-based segmentation  
   - Category contribution to total revenue  

4. **Reporting & KPIs**
   - Customer analytics view with:
     - Recency  
     - Average Order Value  
     - Monthly Spend  
     - Customer Segment  
     - Lifecycle Metrics  

---

## Key KPIs Generated

- Total Sales & Revenue Contribution  
- Customer Lifetime & Recency  
- Average Order Value (AOV)  
- Monthly Spend per Customer  
- Product & Category Performance  
- Year-over-Year Growth Indicators

## Project Structure

- 00_init_database.sql
- 01_database_exploration.sql
- 02_dimensions_exploration.sql
- 03_date_range_exploration.sql
- 04_measures_exploration.sql
- 05_magnitude_analysis.sql
- 06_ranking_analysis.sql
- 07_change_over_time_analysis.sql
- 08_cumulative_analysis.sql
- 09_performance_analysis.sql
- 10_data_segmentation.sql
- 11_part_to_whole_analysis.sql
- 12_report_customers.sql
- 13_report_products.sql

## Learning Outcomes

- Applied SQL to solve real business problems  
- Strengthened understanding of analytical thinking using data  
- Learned how to translate raw data into actionable insights  
- Built production-style SQL queries aligned with BI and analytics roles  

---

## 👤 Author

**Abhishek Yadav**  
MBA (Digital Business) 

- 🔗 LinkedIn: [https://www.linkedin.com/in/abhi76788/](https://www.linkedin.com/in/abhi76788/)
