Supply Chain Management Project

Project Overview

This project aims to optimize supply chain operations, reduce costs, and enhance customer satisfaction by analyzing a comprehensive dataset of supply chain activities. The goal was to identify patterns, optimize inventory, and improve overall performance for a company facing multiple challenges.

Dataset Description

Columns: 53

Rows: 2 lakh

Key Attributes: Order ID, Order Date, Product Category, Sales, Profit, Discount, Customer ID, Customer Segment, Shipping Mode, Delivery Status, Region, and more.

Project Highlights

1. Sales Performance Analysis

Objective: Identify high-performing product categories and regions.

Finding: A linear relationship between product price and sales, indicating that customers prefer high-quality products even at higher prices. For instance, the highest-priced computer ($150) had the highest sales (1300 units).

3. Time Series Order Analysis

Objective: Understand the temporal patterns in order data.

Findings:

October recorded the highest sales, with consistent sales throughout other months.

2017 had the highest number of orders, but a significant dip in sales was observed after October 2017 due to data corruption.

4. Profit and Loss Analysis

Objective: Identify drivers of profit and loss.

Findings: The company had an 80.6% profit rate and 20% loss rate. Detailed region and product-wise analysis revealed areas with significant losses.

5. Statistical Analysis on Discounts

Objective: Determine the impact of discounts on profit and loss.

Method: Bootstrap analysis

Results: With a p-value of 0.46 and confidence level between -0.2 and 0.2, it was concluded that there is no significant difference in the mean discount between profitable and non-profitable transactions.

6. Late Delivery Analysis

Objective: Investigate causes and patterns of late deliveries.

Findings:

90% of late deliveries occurred in first and second-class shipments.

50% of same-day deliveries were late.

Central and Western America had the highest late delivery rates.

7. Fraud Detection and Prevention

Objective: Identify and prevent fraudulent transactions.

Method: Isolation Forest model

Results: Detected a customer (Mary) using different regions as home addresses, leading to 90% of fraud cases. Implementing stricter verification processes based on these insights can prevent such frauds.

8. Inventory Management

Objective: Reduce losses by improving inventory management.

Approach:

ABC Classification: High-value products categorized as 'A' items.

Safety Stock and Reorder Points: Calculated for each product to avoid stockouts and ensure timely deliveries.

9. Customer Segmentation (RFM Analysis)

Objective: Segment customers for targeted marketing strategies.

Method: RFM (Recency, Frequency, Monetary) Analysis

Findings:
Big Spenders: Account for 40% of revenue; require exceptional service.

Bargain Customers: High in number but challenging to retain.

Lost Customers: Represent 27% of total revenue; strategies needed for retention.

10. Market Basket Analysis
    
Objective: Understand product associations and optimize inventory placement.

Method: Association rule mining

Results: Identified frequent product combinations, allowing for better warehouse management and cross-selling strategies.

Business Implications

Improved Customer Satisfaction: By ensuring timely deliveries and retaining high-value customers.

Reduced Operational Costs: Through efficient inventory management and fraud prevention.

Enhanced Revenue: By understanding and targeting key customer segments and optimizing product placement.

Strategic Decision-Making: Data-driven insights enable better decision-making across the supply chain.

Conclusion

This project demonstrates the power of data analysis in transforming supply chain operations. By leveraging statistical methods, machine learning models, and business analytics, significant improvements in efficiency, customer satisfaction, and profitability were achieved.

