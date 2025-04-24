# 🗃️ SQL Database Project: Agent-Customer-Order Management

This project demonstrates the design and usage of a relational database system using SQL. It includes schema creation, data querying, performance optimization, and analysis using views and aggregate functions.

## 📑 Tables and Schema

The database consists of the following tables:

1. **AGENTSS**
2. **CUSTOMER**
3. **ORDERS**

Each table includes appropriate data types, primary keys, and foreign key relationships.

### Schema Overview

- `AGENTSS`: Stores agent information like name, working area, phone, commission, and country.
- `CUSTOMER`: Stores customer details including city, country, financials, and agent code (foreign key).
- `ORDERS`: Stores order transactions linked to both customer and agent.

## 📦 SQL Features Implemented

### ✅ Table Creation
- Structured schema with constraints and data types.

### ✅ Data Querying
- `SELECT`, `WHERE`, `ORDER BY`, `GROUP BY`
- Aggregate functions like `SUM()` and `AVG()`

### ✅ Joins
- `INNER JOIN`
- `LEFT JOIN`
- `RIGHT JOIN`

### ✅ Subqueries
- Nested queries for comparative analysis.

### ✅ Views
- Created views for business analytics:
  - `HighValueOrders`: Orders above a threshold
  - `CustomerAgentView`: Combines customer and agent details

### ✅ Performance Optimization
- Added indexes on critical columns:
  - `ORDERS(CUST_CODE)`
  - `CUSTOMER(AGENT_CODE)`
  - `ORDERS(ORD_AMOUNT)`
