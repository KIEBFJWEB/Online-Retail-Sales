``**Objective**
The primary objective of this project is to analyze the retail sales data to:

Assess Sales Performance: Identify top-selling products, high-performing regions, and evaluate sales trends over time.
Understand Customer Behavior: Segment customers based on purchasing frequency, total spending, and preferences.
Optimize Inventory and Pricing: Examine inventory movement and pricing patterns to guide stock management and pricing strategies.
Enhance Business Decision-Making: Generate actionable insights from data that can support strategic decisions in marketing, inventory planning, and customer relationship management.

**DATASETS** 
CREATE DATABASE ONLINE_RETAIL;
USE ONLINE_RETAIL;


CREATE TABLE RETAIL_SALES
(
INVOICE_NO INT,
STOCK_CODE VARCHAR(20), 
DESCRIPTION VARCHAR(30), 
QUANTITY INT, 
INVOICE_DATE VARCHAR(30), 
UNIT_PRICE INT, 
CUSTOMER_ID INT, 
COUNTRY VARCHAR(30)) ;

SELECT * FROM RETAIL_SALES;


