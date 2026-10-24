
# Ecommerce Delivery Analysis
## Week 1 Report: Data Exploration and Initial Analysis

### 1. Project Objective
The objective of this project is to analyze e-commerce sales,
profit, and delivery performance to identify business trends
and opportunities for improvement.

### 2. Dataset Overview
- Total records: 180,519
- Original columns: 53
- Duplicate rows: 0
- Dataset format: CSV

### 3. Data Cleaning
- Removed the Product Description column because all its values were missing.
- Removed the Order Zipcode column because most values were missing.
- Replaced missing Customer Lname values with "Unknown".
- Identified 3 remaining missing values in Customer Zipcode.
- Converted order date and shipping date columns to datetime format.
- Created Delivery_Delay and Delivery_Performance columns.

### 4. Overall Business KPIs
- Total sales: 36,784,735.01
- Total profit: 3,966,902.97
- Total dataset records: 180,519
- Average delivery delay: 0.57 days
- Late delivery percentage: 57.28%

### 5. Delivery Performance Findings
- Late deliveries: 57.28%
- Early deliveries: 24.02%
- On-time deliveries: 18.70%
- First Class had 100% late deliveries in this dataset.
- Same Day had 52.17% on-time deliveries.
- Central Asia had the highest average regional delivery delay.
- Golf Bags & Carts had the highest average category delivery delay.

### 6. Sales and Profit Findings
- Fishing generated the highest total sales among the product categories.
- Fishing also generated the highest total profit.
- Monthly sales peaked in September 2017.
- Monthly profit peaked in August 2017.
- Sales and profit decreased significantly toward the end of 2017.

Note: January 2018 may represent an incomplete period, so it should
not be compared directly with complete months.

### 7. Visualizations Created
- Delivery performance distribution
- Delivery performance by shipping mode
- Top 10 product categories by average delivery delay
- Top 10 regions by average delivery delay
- Average delivery delay by market
- Top 10 customers by total sales
- Top 10 product categories by total sales
- Top 10 product categories by total profit
- Monthly sales trend
- Monthly profit trend

### 8. Conclusion
Initial exploratory data analysis revealed that late deliveries
are a major area for investigation. Fishing is the leading
category in both sales and profit. Further analysis will explore
delivery performance, business KPIs, and possible improvements.

### 9. Week 1 Status
Data loading, initial cleaning, exploratory analysis, and
visualization are substantially complete. Documentation and
GitHub organization are in progress.
