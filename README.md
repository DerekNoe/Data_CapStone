About Dataset

The purpose of this fictional sales dataset is to provide data for Data Analysis practice. The 3 tables must be joined before one can analyze the data.

This fictional data set consists of 3 tables:

Customer dimension (history preserving) Product dimension (history preserving) Sales Transactions The Customer Dimension dataset includes unique customer IDs, addresses, ages, and indicators of current records, with effective start and end dates for each customer.

The Product Dimension dataset details unique product IDs, names, prices, and their validity periods, along with indicators of current price records.

The Sales Transactions dataset captures sales activities with unique order IDs, product IDs, customer IDs, quantities sold, and order dates. Together, these datasets offer a comprehensive view of customer demographics, product pricing history, and sales transactions.
Customer Data Table
.
.
.
.
Data Dictonary 
.
cust_id- Unique ID for each order.

cust_address- Customers address.

cust_age- Age of the customer.

effective_start_date- The date when the product's price became effective.

effective_end_date- The date when the product's price record will expire .

current_ind- Indicator if the price record is current (Yes/No).
.
.
.
Product Data Table

product_id- Unique ID for each product.

product_name- Name of the product.

product_price- Price of the product.

effective_start_date- The date when the product's price became effective.

effective_end_date- The date when the product's price record will expire .

current_ind- Indicator if the price record is current (Yes/No).
.
.
.
Sales Transactions

order_id- Unique ID for each order.

product_id- ID for product in the order.

cust_id- ID for the customer who made the order.

product_quantity- Quantity of the product ordered.

order_date- Date the product was ordered.