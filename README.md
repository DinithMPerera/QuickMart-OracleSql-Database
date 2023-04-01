# QuickMart-OracleSql-Database
Creating an enhanced ERD, building a database and Populating it with test data to write queries. 

QuickMart - A Retail Grocery Chain



SCENARIO:
 
You are to model and build a database to enable a retail grocery chain named QuickMart to have better intelligence regarding their customer purchasing patterns to provide a more personalized shopping experience to their customers. The following explains the typical elements, operations and their interactions of this function of a retail store chain.
 
A retail store chain has many outlets. An outlet has a unique 4-digit code, province, district, city, address and 10-digit telephone number.

The type of product sold at a retail chain has a manufacturer, price and product category associated with it. Apart from this, a product would have a product ID and name. A manufacturer has a name, a 10-digit registration code and an address. A category is simply a name that identifies a product group (i.e. men's Perfume, Diapers, Non-fat Fresh Milk etc.)

There will be multiple counts of a product in a store. Each unit of a product is called an SKU (Stock Keeping Unit). A stock-keeping unit will have a 36-character (alphanumeric) code, a product ID, an outlet ID and a batch code assigned to it. A batch would have a product ID, manufactured date and expiration date and retail price. SKUs with an outlet ID ‘0000’ are considered to be in the warehouse.

A customer who has registered with the loyalty program would have a first and last name, DoB in (YYYY-MM-DD) format, National Identity Card Number (NIC), a gender, a 10-digit mobile number and a loyalty card. A loyalty card would have a loyalty card number, issued date, expiry date and retail price associated with it.

A customer purchase history record will be required for each purchase that a customer makes. A purchase history record will have a bill number and an SKU associated with it.

A bill represents a collection of SKUs that a customer purchased in one go. A bill would have a date, outlet ID and customer loyalty card number. For customers without a loyalty card system generated customer ID is available in the bill.

After every purchase relevant items from the warehouse depletes. When it reaches a threshold, an order is created for the supplier automatically.

Loyalty cardholders get special discounts on certain products. Discount is calculated as a percentage of the retail price and discount percentage is defined for a period.
 



REQUIREMENTS
 

1. Having been briefed on RetailX’s requirements, you are expected to develop an accurate entity model to represent it.
 
2. Write the DDL (SQL Code) for defining the table structure and implement the right primary and foreign key constraints.
 
3. Populate the tables with appropriate test data.

