E-commerce data analysis

![e-commerce](https://www.x-cart.com/wp-content/uploads/2019/01/ecommerce-768x278.jpg)

To give a brief overview, this notebook is dedicated to sections as follow:

    Context of Data
    Data Cleaning (a.k.a data preprocessing)
    Exploratory Data Analysis
    Model results
    Conclusion

Context of Data
----------
The dataset consists of transactional data with customers in different countries who make purchases from an online retail company based in the United Kingdom (UK) that sells unique all-occasion gifts. The information is summarized as below:

    Company              — UK-based and registered non-store online retail
    Products for selling — Mainly all-occasion gifts
    Customers            — Most are wholesalers (local or international)
    Transactions Period  — 1st Dec 2010–9th Dec 2011 (One year)

The analysis and optimization for storage area (i.e. storage area is expensive so we want to keep the products which give us the best revenue). Keeping in mind that fast delivery is also critical so we like to help the retailer by predicting the amount of sold product. There are missing values in the data, optimization is done by doing the analysis.

**Please note the assignment is done in Python. Use the below data dictionary for your reference:**

    InvoiceNo (invoice_num)   : A number assigned to each transaction
    StockCode (stock_code)    : Product code
    Description (description) : Product name
    Quantity (quantity)       : Number of products purchased for each transaction
    InvoiceDate (invoice_date): Timestamp for each transaction
    UnitPrice (unit_price)    : Product price per unit
    CustomerID (cust_id)      : Unique identifier each customer
    Country (country)         : Country name

Model Training
---------
    Linear Regression
    Decision Tree Regression
    Random Forest Regression

Author @vikashryder
