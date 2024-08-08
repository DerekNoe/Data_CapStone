# Dataset Overview

The objective of this fictional sales dataset is to facilitate data analysis practice. It comprises three distinct tables:

  1. Customer Dimension (History Preserving): This table contains unique customer IDs, addresses, ages, and indicators of current records, along with effective start and end dates for each customer.

  2. Product Dimension (History Preserving): This dataset includes unique product IDs, names, prices, and their validity periods, in addition to indicators of current price records.

  3. Sales Transactions: This table captures sales activities with unique order IDs, product IDs, customer IDs, quantities sold, and order dates.

Together, these datasets provide a comprehensive view of customer demographics, product pricing history, and sales transactions.

### Project Objective

The aim of this project was to simulate the presentation of sales information to company managers. I segmented the sales data by state and age group to identify key markets and demographic trends. This analysis highlights where the majority of sales originate and which age groups are primarily responsible for purchases.

### Methodology

**Data Extraction and Analysis:** I utilized the Pandas library in Python to extract and analyze data from each dataframe.
<br>
**Visualization:** To enhance the visual presentation of the analysis, I employed the Seaborn library. The visualizations included bar charts, a pie chart, and a word cloud.
Data Dictionary

Below is a data dictionary providing specific details regarding the information presented in each of the three datasets.


<br>
<br>

## Data Dictionary 
<br>

#### Customer Data Tabel  

cust_id- Unique ID for each order.

cust_address- Customers address.

cust_age- Age of the customer.

effective_start_date- The date when the product's price became effective.

effective_end_date- The date when the product's price record will expire .

current_ind- Indicator if the price record is current (Yes/No).
<br>
<br>
#### Product Data Table

product_id- Unique ID for each product.

product_name- Name of the product.

product_price- Price of the product.

effective_start_date- The date when the product's price became effective.

effective_end_date- The date when the product's price record will expire .

current_ind- Indicator if the price record is current (Yes/No).
<br>
<br>
#### Sales Transactions

order_id- Unique ID for each order.

product_id- ID for product in the order.

cust_id- ID for the customer who made the order.

product_quantity- Quantity of the product ordered.

order_date- Date the product was ordered.
