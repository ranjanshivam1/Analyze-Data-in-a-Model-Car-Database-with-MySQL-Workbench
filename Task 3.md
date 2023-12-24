## Task 3 — Investigating Business Issues and Identifying Affected Tables

## 1. Identifying Overstocked Products with Low Sales: 
This query aims to find products that have excessive inventory levels but comparatively low sales. By comparing the quantity of the product available in stock against the total quantity ordered, we can identify products with an inventory surplus.

<img width="429" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/f95f8d07-890a-42e3-acef-fb4542ccef92">

https://drive.google.com/file/d/1XFF1yJTNGacSnp9Aj-30DlVob7GUvUzf/view?usp=sharing


## 2. Assessing Warehouse Utilization: 
These queries analyze the inventory in each warehouse to determine if all warehouses are necessary. One query sorts the product-warehouse combinations based on the lowest total inventory to evaluate the underutilized warehouses, while the other lists warehouses by their total inventory to assess the ones with the highest stock.

## 3. Examining Price-Sales Relationship: 
This query retrieves product data and purchase prices, grouping by product and ordering by purchase price. It helps in understanding if higher prices correlate with higher sales and how changes in prices might affect sales levels.

## 4. Identifying Key Customer Contributions:
By joining customer and order tables and grouping by customer, this query identifies customers contributing the most to sales. It sorts customers based on their total sales amount to pinpoint the most valuable ones.

## 5. Evaluating Sales Employee Performance:
These queries involve multiple table joins to evaluate sales employee performance. They group data by employees and their sales, sorting employees based on their total sales amount to recognize the top performers.

## 6. Analyzing Customer Payment Trends: 
This query retrieves customer payment data and sorts it by payment amount, enabling the analysis of customer payment behavior and identification of high-paying customers.

## 7. Comparing Product Line Performance: 
By combining product and order details, this query groups data by product lines, analyzing the performance of each line based on inventory, sales, revenue, and sales-to-inventory percentage. It orders product lines by their sales-to-inventory percentage to highlight the most successful lines.

## 8. Evaluating Credit Policies and Customer Payments: 
This query joins customer and payment tables, grouping by customers and credit limits. It filters customers whose total payments are less than their credit limits, allowing assessment of credit risks and identification of customers with potential credit issues.

These queries collectively aim to provide insights into inventory optimization, warehouse utilization, sales patterns, employee performance, customer behaviors, product line success, and credit policy evaluation at Mint Classics.
