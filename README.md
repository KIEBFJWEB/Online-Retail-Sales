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

**QUESTIONS** 

-- What is the total revenue generated?
                                         -- Which product (Stock_Code) has the highest sales volume (total Quantity)?
-- What is the average revenue per invoice?
-- Which day had the highest total sales based on Invoice_Date?
#  Customer Insights

-- Who are the top 5 customers by total purchase amount (Unit_Price * Quantity)?
-- How many unique customers are there in the dataset?
-- Which customers have placed the most orders?
-- What is the average order value per customer?
# Product Analysis

-- Which products are the top 5 most sold items by quantity?
-- What is the average quantity sold per product?
-- Are there any products that have consistently low sales volume?
-- Which products have the highest total revenue?
# Country-based Analysis

-- Which country generates the most revenue?
-- What is the average order quantity per country?
-- Are there countries with significantly higher or lower average order values?
-- How many unique customers are there per country?
# Sales Patterns Over Time

-- What are the monthly sales trends?                                                                      
-- Is there any noticeable seasonal trend in the sales?
-- What is the most common day of the week for purchases?
-- How does sales performance compare year over year?
# Order Details

-- How many orders contain multiple items?
-- What is the average number of items per invoice?
-- Are there any patterns in high-quantity orders by specific customers?
-- What is the average order size in terms of quantity?
# Price Sensitivity

-- How does revenue vary across different price ranges of products?
-- Which price range generates the highest sales volume?
-- Are there products with a higher price that still have high sales volumes?
# Customer Retention and Loyalty

-- How many customers have repeat purchases?
-- What is the average time between repeat purchases for each customer?
-- Which customers are the most frequent buyers?
``
