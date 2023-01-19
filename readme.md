# Improving Customer Centricity in eCommerce
![python 3.9.1](https://img.shields.io/pypi/pyversions/pandas?color=green&label=python)
![pandas 1.5.2](https://img.shields.io/badge/pandas-1.5.2-blue)

### **Introduction**
This project looks like a template for an exploratory business analysis of a company based on selling commercial services or products to customers.

### **The main goals of this project:**
- To find out the number of users in the dataset who made only one purchase;
- To find out the average number of non-deliverable orders per month, detailing their reasons;
- To identify a favorable day of the week to buy each product.
- To find the average number of purchases per week for each customer.
- To perform a Cohort Analysis of the data and find the highest Retention Rate in the third month.
- To perform an RFM Analysis of the data for each user and average the RFM-metrics for each cluster.

### **The designation of columns in the datasets:**
1. Customers dataset:
- customer_id — custom user ID (similar to passport number);
- customer_unique_id — unique user ID;
- customer_zip_code_prefix — user's zip code;
- customer_city — user delivery city;
- customer_state — user's delivery state.
2. Order dataset:
- order_id — unique order identifier (receipt number);
- customer_id — custom user ID (similar to passport number);
- order_status — order status;
- order_purchase_timestamp — order creation time;
- order_approved_at — order payment confirmation time;
- order_delivered_carrier_date — time of transferring the order to the logistics service;
- order_delivered_customer_date — order delivery time;
- order_estimated_delivery_date — estimated delivery date.
3. Items order dataset:
- order_id — unique order identifier (receipt number);
- order_item_id — item identifier within one order;
- product_id — product id (analogue of a barcode);
- seller_id — id of the product manufacturer;
- shipping_limit_date — maximum date of delivery by the seller to transfer the order to the logistics partner;
- price — price per item;
- freight_value — goods weight.