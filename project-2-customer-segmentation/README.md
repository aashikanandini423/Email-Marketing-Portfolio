# Project 2: Customer Segmentation & SQL-Based Targeting

## Objective
Use SQL to segment customers into actionable groups for targeted marketing campaigns.

## Dataset Overview
Fields used:
- customer_id
- email
- total_orders
- total_spent
- last_purchase_date

## Business Problem
Generic campaigns result in low engagement due to lack of personalization.

## Solution
Created behavioral segments to target users with relevant messaging.

## Segments & SQL Logic
1. High-Value Customers
```sql
SELECT *
FROM customers
WHERE total_spent > 500;

### 2.Inactive Customers (Win-back)
```sql
SELECT *
FROM customers
WHERE last_purchase_date < '2025-01-01';

### 3.Frequent Buyers
```sql
SELECT *
FROM customers
WHERE total_orders >= 5;
