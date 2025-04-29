# 📊 SQL Report: 6-Month Revenue & Order Volume Summary

This SQL script generates a monthly summary of **total revenue** and **distinct order volume** from the `ORDERS` table, focusing on the **last 6 months**.

## ✅ Features

- Extracts **year** and **month** from the `ORD_DATE`
- Calculates:
  - `SUM(ORD_AMOUNT)` → total revenue
  - `COUNT(DISTINCT ORD_NUM)` → total number of orders
- Filters data to the **last 6 months**
- Sorted by year and month (latest first)
