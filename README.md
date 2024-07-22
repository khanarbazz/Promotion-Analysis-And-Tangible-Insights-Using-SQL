# AtliQ Mart’s Promotions Analysis and Tangible Insights!

This repository contains the SQL scripts used to analyze the performance of promotional campaigns run by AtliQ Mart during Diwali 2023 and Sankranti 2024. The project addresses various business requests related to identifying high-value discounted products, store distribution, campaign effectiveness, and product performance in terms of incremental sales and revenue.

## Introduction

Promotions are a pivotal aspect of retail strategy, especially during festive seasons. This project focuses on evaluating the impact of promotional campaigns conducted by AtliQ Mart during Diwali 2023 and Sankranti 2024. By analyzing various metrics such as incremental revenue, sold units, and store performance, this analysis aims to provide actionable insights to enhance future promotional strategies and maximize returns.

## Data Sources

The analysis is based on data provided by AtliQ team. The main datasets provided include fact_events, dim_products, dim_stores, and sales_summary. These datasets contain information about product sales, store locations, promotional events, and campaign revenues.

## Project Overview:

1. Conducted a detailed analysis of promotional campaigns during Diwali 2023 and Sankranti 2024 using AtliQ Mart's internal data.
2.Executed SQL queries to address key business requests focused on product, store, and campaign performance.
3.Identified high-value products, analyzed store distribution, and evaluated the effectiveness of various promotion types.
4.Generated actionable insights to optimize future marketing strategies and improve overall sales performance.

## Business Requests

### 1. High-Value Products in BOGOF Promotion
**Query:**
Provide a list of products with a base price greater than 500 and that are featured in the promo type of 'BOGOF' (Buy One Get One Free).

**Purpose:**
Identify high-value products that are currently being heavily discounted, which can be useful for evaluating pricing and promotion strategies.

### 2. Store Count by City
**Query:**
Generate a report that provides an overview of the number of stores in each city. The results will be sorted in descending order of store counts.

**Purpose:**
Identify the cities with the highest store presence, assisting in optimizing retail operations.

### 3. Campaign Revenue Impact
**Query:**
Generate a report that displays each campaign along with the total revenue generated before and after the campaign.
**Purpose:**
Evaluate the financial impact of promotional campaigns.

### 4. Campaign Revenue Impact
**Query:**
Produce a report that calculates the Incremental Sold Quantity (ISU%) for each category during the Diwali campaign. Provide rankings for the categories based on their ISU%.
**Purpose:**
Assess the category-wise success and impact of the Diwali campaign on incremental sales.

### 5. Top 5 Products by IR%
**Query:**
Create a report featuring the Top 5 products, ranked by Incremental Revenue Percentage (IR%), across all campaigns.n.
**Purpose:**
Identify the most successful products in terms of incremental revenue across campaigns, assisting in product optimization.


## Results and Insights

The analysis revealed several key insights:

-Identify high-value BOGOF products and assess their impact on discounting strategies.
-Determine top and bottom-performing stores based on incremental revenue and sold units, and analyze city-wise store performance.
-Evaluate promotion types to find the most effective for revenue generation and the least impactful on sold units.
-Analyze product categories and specific products for significant sales lifts from promotions and their responsiveness to different promotion types.
-Review revenue impact before and after campaigns and rank categories and products by incremental sales and revenue percentage.

These insights can help AtliQ Mart make informed decisions for future promotional activities, optimize resource allocation, and improve overall sales performance.

## Conclusion

Overall, the analysis provides valuable insights into the performance of promotional campaigns conducted by AtliQ Mart during Diwali 2023 and Sankranti 2024. By leveraging data analytics, AtliQ Mart can enhance its marketing strategies, attract more customers, and drive higher sales during festive seasons.

## Additional Insights

In addition to the main business requests, the following recommended insights were explored during the analysis:

### Store Performance Analysis

- **Top 10 Stores by Incremental Revenue (IR):** Identify the top-performing stores in terms of incremental revenue generated from promotions.
- **Bottom 10 Stores by Incremental Sold Units (ISU):** Identify the stores with the lowest performance in terms of incremental sold units during the promotional period.
- **City-wise Store Performance:** Analyze how store performance varies by city and identify any common characteristics among top-performing stores.

### Promotion Type Analysis

- **Top 2 Promotion Types by Incremental Revenue:** Determine the top-performing promotion types that resulted in the highest incremental revenue.
- **Bottom 2 Promotion Types by Incremental Sold Units:** Identify the least effective promotion types in terms of their impact on incremental sold units.
- **Comparison of Promotion Types:** Analyze the performance differences between discount-based promotions, BOGOF (Buy One Get One Free), and cashback promotions.
- **Optimal Promotion Type:** Determine which promotions strike the best balance between incremental sold units and maintaining healthy margins.

### Product and Category Analysis

- **High-Lifting Product Categories:** Identify product categories that saw significant increases in sales from the promotions.
- **Product Responsiveness to Promotions:** Analyze specific products that respond exceptionally well or poorly to promotions.
- **Correlation between Product Category and Promotion Type 
