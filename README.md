# 🏍️ Analyzing Motorcycle Parts Sales with SQL

![Parked motorcycle](motorcycle.jpg)

## 📖 Project Overview

You're working for a company that sells motorcycle parts, and they've asked for some help in analyzing their sales data!

They operate three warehouses in the area, selling both retail and wholesale. They offer a variety of parts and accept credit cards, cash, and bank transfer as payment methods. However, each payment type incurs a different fee.

The board of directors wants to gain a better understanding of wholesale revenue by product line, and how this varies month-to-month and across warehouses. You have been tasked with calculating net revenue for each product line and grouping results by month and warehouse. The results should be filtered so that only `"Wholesale"` orders are included.

They have provided you with access to their database, which contains the following table called `sales`:

## Sales
| Column | Data type | Description |
|--------|-----------|-------------|
| `order_number` | `VARCHAR` | Unique order number. |
| `date` | `DATE` | Date of the order, from June to August 2021. |
| `warehouse` | `VARCHAR` | The warehouse that the order was made from&mdash; `North`, `Central`, or `West`. |
| `client_type` | `VARCHAR` | Whether the order was `Retail` or `Wholesale`. |
| `product_line` | `VARCHAR` | Type of product ordered. |
| `quantity` | `INT` | Number of products ordered. | 
| `unit_price` | `FLOAT` | Price per product (dollars). |
| `total` | `FLOAT` | Total price of the order (dollars). |
| `payment` | `VARCHAR` | Payment method&mdash;`Credit card`, `Transfer`, or `Cash`. |
| `payment_fee` | `FLOAT` | Percentage of `total` charged as a result of the `payment` method. |

---

## 🎯 Business Problem

The company sells motorcycle parts through multiple warehouses and serves both **Retail** and **Wholesale** customers.

Since different payment methods incur different transaction fees, management wanted to know the **actual net revenue** generated from wholesale sales after deducting payment fees.

---

## 🛠️ Technologies Used

- PostgreSQL
- SQL
- DataCamp DataLab

---

## 📌 SQL Concepts Demonstrated

- SELECT
- WHERE
- GROUP BY
- SUM()
- TO_CHAR()
- ORDER BY

---

data Source: Datacamp Datalab 

## 👨‍💻 Author

**Himanshu Kumar**

GitHub: https://github.com/himucodes-7

LinkedIn: https://www.linkedin.com/in/himanshu-kumar-aiml/

---

---
*If you have any feedback or want to chat about the approach, feel free to open an issue or reach out!*
