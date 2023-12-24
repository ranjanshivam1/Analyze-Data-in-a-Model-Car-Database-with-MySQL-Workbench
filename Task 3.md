## Task 3 — Investigating Business Issues and Identifying Affected Tables

## 1. Identifying Overstocked Products with Low Sales: 
<img width="283" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/7213612f-bcf4-4c89-8ea9-5f177b4f4344">


This query aims to find products that have excessive inventory levels but comparatively low sales. By comparing the quantity of the product available in stock against the total quantity ordered, we can identify products with an inventory surplus.

<img width="429" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/f95f8d07-890a-42e3-acef-fb4542ccef92">

## 2. Assessing Warehouse Utilization:
<img width="367" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/5557ea50-b504-40ca-9602-920dc171065c">

<img width="355" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/ead3561a-e321-4d25-9c30-6845cd8f98da">

These queries analyze the inventory in each warehouse to determine if all warehouses are necessary. One query sorts the product-warehouse combinations based on the lowest total inventory to evaluate the underutilized warehouses, while the other lists warehouses by their total inventory to assess the ones with the highest stock.
<img width="265" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/10976fe2-49b4-4792-9b28-3c7046656b94">
<img width="236" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/817ce9a7-a6ab-496b-9e04-098153c25f8a">


## 3. Examining Price-Sales Relationship: 
<img width="364" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/32fc2edf-d53f-4881-a24a-588778e149f7">


This query retrieves product data and purchase prices, grouping by product and ordering by purchase price. It helps in understanding if higher prices correlate with higher sales and how changes in prices might affect sales levels.
<img width="336" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/802fb243-f8f7-4f15-9b63-e655ba558a81">


## 4. Identifying Key Customer Contributions:
<img width="352" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/bbb70ec0-b4f1-4b8d-af2e-ccfe69369898">

By joining customer and order tables and grouping by customer, this query identifies customers contributing the most to sales. It sorts customers based on their total sales amount to pinpoint the most valuable ones.
<img width="263" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/f599f221-0635-45d7-87c3-ad08b102b734">


## 5. Evaluating Sales Employee Performance:
<img width="411" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/51b77b88-4628-4661-a989-95fd721ec0cd">

These queries involve multiple table joins to evaluate sales employee performance. They group data by employees and their sales, sorting employees based on their total sales amount to recognize the top performers.
<img width="295" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/24b2db39-ecaa-47a5-bf56-786f7751c7bb">


## 6. Analyzing Customer Payment Trends: 
<img width="362" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/79bac9fc-cf60-4bfb-bfa1-a6412a87b8ab">

This query retrieves customer payment data and sorts it by payment amount, enabling the analysis of customer payment behavior and identification of high-paying customers. 
<img width="336" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/e25b55a4-2edc-4918-b7af-3f356cd6d187">


## 7. Comparing Product Line Performance:
<img width="470" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/aa7ef396-1a85-4dd6-8ec6-f7a36690155c">

By combining product and order details, this query groups data by product lines, analyzing the performance of each line based on inventory, sales, revenue, and sales-to-inventory percentage. It orders product lines by their sales-to-inventory percentage to highlight the most successful lines.
<img width="580" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/584f7e51-ea1d-40b5-921b-7ef6af77da15">


## 8. Evaluating Credit Policies and Customer Payments: 
<img width="412" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/953b0271-fd97-4bb0-9ca6-e60b4641cb59">

This query joins customer and payment tables, grouping by customers and credit limits. It filters customers whose total payments are less than their credit limits, allowing assessment of credit risks and identification of customers with potential credit issues.

<img width="431" alt="image" src="https://github.com/ranjanshivam1/Analyze-Data-in-a-Model-Car-Database-with-MySQL-Workbench/assets/132743857/9c507fb5-77a8-4661-b610-8b8186e7eb82">



These queries collectively aim to provide insights into inventory optimization, warehouse utilization, sales patterns, employee performance, customer behaviors, product line success, and credit policy evaluation at Mint Classics.
