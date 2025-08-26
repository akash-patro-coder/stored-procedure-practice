#📂 Databricks SQL: Dynamic Customer & Orders Queries
##Description

This repository contains dynamic SQL queries and reusable views for analyzing customers and orders tables in Databricks. The goal is to provide a fully reusable and parameterizable framework for querying, joining, and checking data without rewriting code for each scenario.

Key highlights include:

✅ Reusable Views: customer_orders_view for joining customers with orders.

✅ Dynamic Queries: Use of Databricks SQL widgets and Python to run parameterized joins or filters.

✅ Schema Checks: Commands to inspect table structure (DESCRIBE TABLE, SHOW COLUMNS) and confirm column existence.

✅ Data Quality Checks: Quick checks for row counts, distinct values, and orphaned records.

✅ Analytics Queries: Examples of common reporting queries like total orders per customer, customers with no orders, first order date, and aggregations by city or gender.

✅ Notebook-Ready: All queries are organized to run in Databricks notebooks for seamless experimentation.
