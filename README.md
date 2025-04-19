# Monthly Revenue and Order Volume Report

This project analyzes revenue and order volume on a monthly basis using SQL queries on an `orders` table.
## 📋 Table Structure

The table used in this analysis:

```sql
CREATE TABLE orders (
    ord_no INT,
    purch_amt DOUBLE,
    ord_date VARCHAR(512),
    customer_id INT,
    salesman_id INT
);
