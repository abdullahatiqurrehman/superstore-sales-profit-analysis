# Super Store Analysis #
This project analyzes the Superstore dataset to understand sales performance, profitability, discounting, regional performance, and potential areas of business risk.

The analysis focuses on identifying where the business is generating revenue but losing profitability and provides recommendations based on the findings.

# 🎯 Business Objectives

The analysis aims to answer the following questions:

1. Does heavy discounting negatively affect profitability?
2. Is the Furniture category performing efficiently?
3. Which product sub-categories are generating losses?
4. Which states are negatively affecting overall profit?
5. Which regions contribute the most to profitability?
6. How significant are loss-making orders?
7. How does sales and profit performance vary throughout the year?

# 🗃️ Dataset
The dataset is a USA Superstore order-history dataset sourced from Kaggle.

Dataset period: January 2014 – December 2017,
Customers: 793,
States: 49,
Rows: Approximately 10,000, and
Columns: 21

Major Columns:
Order ID,
Order Date,
Ship Date,
Ship Mode,
Customer ID,
Customer Name,
Segment,
City,
State,
Postal Code,
Region,
Product ID,
Category,
Sub-Category,
Unit Price,
Quantity,
Discount, and
Profit

# 🛠️ Tools Used
Microsoft Excel,
Data Analysis,
Data Visualization,
Pivot Tables / Charts, and
Business Intelligence techniques

# 🔍 Key Business Findings
1. Heavy Discounts Suppress Profitability: 
The analysis shows that increasing discounts can significantly reduce profitability.
At discounts above 20%, the business can generate sales while experiencing severely reduced or negative profit.
Recommendation:
Limit standard discounts to 20%,
Require approval for discounts above 20%, and
Monitor high-discount orders closely

2. Furniture Has Low Profitability: 
Furniture contributes approximately 32% of sales but only 6% of total profit.
This indicates that the category generates significant revenue but provides relatively little profit compared with the effort and inventory involved.
Recommendation:
Review Furniture pricing,
Reduce excessive discounting,
Investigate low-margin products, and
Focus on improving category-level profitability

3. Tables Are a Major Profit Leak: 
Tables are identified as the largest loss-making sub-category, with approximately -$17.7K in profit.
Increasing sales of an unprofitable product can potentially increase the overall loss.
Recommendation:
Review Table pricing,
Reduce excessive discounts,
Consider bundling Tables with profitable products, and
Investigate product-level costs and margins

4. Certain States Are Destroying Profit: 
Three states with significant negative profit were identified:
State; Profit
Texas; -$25.7K
Ohio; -$16.9K
Pennsylvania; -$15.6K
These markets require further investigation because they reduce profits generated in other regions.
Recommendation:
Review regional pricing,
Investigate discounting patterns,
Analyze product mix and shipping costs, and
Develop state-level profitability strategies

5. Regional Performance
The West region is the strongest contributor to profit.
The Central region requires additional investigation because its revenue contribution is relatively high compared with its profit contribution.
Region; Sales; Profit
Central; $501.2K; $39.7K
East; $678.8K; $91.5K
South; $391.7K; $46.7K
West; $725.5K; $108.4K

# ⚠️ Hidden Risk: Loss-Making Orders
Approximately 19.4% of orders are loss-making.
That means nearly 1 in 5 orders generates a negative profit.
Recommendation:
Implement monitoring or alerts for:
Orders with discounts above the defined threshold,
Orders with negative profit margins, and
Products with consistently negative profitability

# 📅 Monthly Performance
The analysis also examines revenue and profit across months from 2014–2017.
February recorded the lowest sales at approximately $240.8K and the lowest profit at approximately $10.2K.
December recorded the highest sales at approximately $1.54M and the highest profit at approximately $43.3K.
This indicates a strong seasonal effect in the business.

# 💡 Business Recommendations
Based on the analysis, the following actions are recommended:
> Control discounting.
> Set a 20% standard discount threshold.
> Require approval for higher discounts.
> Improve Furniture profitability
> Review pricing and product margins.
> Reduce unnecessary discounts.
> Address loss-making products
> Investigate Tables and other negative-profit sub-categories.
> Consider repricing or bundling strategies.
> Review underperforming states
> Analyze pricing, discounts, shipping costs, and product mix.
> Monitor loss-making orders
> Create alerts for negative-profit orders.
> Monitor high-discount transactions.
> Track profitability alongside revenue
> Revenue growth should not be evaluated without considering profit margin.

# 📈 Key Takeaway
The business does not have a sales problem — it has a profitability management problem.
Revenue is strong, but profitability is affected by excessive discounting, underperforming products, loss-making states, and regional differences.
The analysis suggests that improving discount management and addressing underperforming products and markets could provide a meaningful improvement in profitability.

# 📊 Recommended KPIs to Monitor
Management should regularly monitor:
Total Sales,
Profit,
Profit Margin %,
Profit by Region,
Sales by Segment,
Discount %,
Average Profit, and
Loss-Making Orders

# 📸 Dashboard / Analysis Preview
<img width="1310" height="748" alt="image" src="https://github.com/user-attachments/assets/d049ff95-b406-4520-b3cc-6daf149402c8" />

# 👨‍💻 Author
Abdullah Atiq Ur Rehman
Computer Engineering Student
Interested in Data Analytics, Business Intelligence, SQL, Excel, Power BI, and Python.
