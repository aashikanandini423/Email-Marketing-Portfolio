# Project 2: Customer Segmentation & SQL-Based Targeting
## Description

Developed SQL-based customer segmentation to enable targeted and personalized marketing campaigns.

Analyzed customer data to identify key segments such as high-value users, inactive users, and frequent buyers using behavioral and transactional attributes. Wrote SQL queries to extract actionable insights and support campaign targeting.

Applied segmentation strategies to align marketing messages with user behavior, improving relevance and engagement. Demonstrated how data-driven segmentation can enhance campaign performance and optimize resource allocation.

## Objective
Use SQL to segment customers into actionable groups for targeted marketing campaigns.

## Dataset Overview
Fields used:
- customer_id
- firstname
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
