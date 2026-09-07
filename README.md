# Food Delivery Analytics Dashboard

An interactive Power BI dashboard built to analyze food delivery operations, sales performance, customer behavior, restaurant performance, and delivery efficiency.


## Project Overview

This project analyzes a food delivery dataset containing **200K orders, ₹165M revenue, 56K restaurants, and 20K customers**.

The dashboard provides an interactive view of key business metrics and helps identify patterns across customers, restaurants, cities, cuisines, pricing, ratings, and delivery performance.

## Key KPIs

- Total Orders
- Total Revenue
- Average Order Value
- Average Delivery Time
- Total Customers
- Total Restaurants
- Delivered Orders
- Cancelled Orders
- Cancellation Rate
- Late Delivery Rate
- Repeat Customers
- Orders per Customer
- Average Restaurant Rating
- Average Restaurant Votes

## Analysis Performed

### Customer Analysis
- New vs. repeat customer analysis
- Repeat customer percentage
- Orders per customer
- Customer behavior and order patterns

### Restaurant Analysis
- Restaurant performance
- Rating analysis
- Vote analysis
- Cost-for-two segmentation
- High and low performing restaurants

### Delivery Analysis
- Delivery time analysis
- On-time vs. late deliveries
- Late delivery percentage
- Delivery performance trends

### Geographic & Category Analysis
- City-level performance
- Cuisine analysis
- Restaurant pricing analysis
- Rating-based restaurant segmentation

## DAX

Developed custom DAX calculated columns and measures for:

- Revenue and order KPIs
- Average Order Value
- Delivery performance
- Cancellation metrics
- Repeat customer analysis
- Restaurant performance
- Rating and cost segmentation

Example:

```DAX
Avg Order Value =
DIVIDE([Total Revenue], [Total Orders])
