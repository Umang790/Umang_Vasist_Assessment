# Umang_Vasist_Assessment
# Amazon E-Commerce Sales & Performance Analysis 
# Q1. Dataset Information 
Dataset: Amazon E-commerce Sales Dataset 
Source: Kaggle 
Rows: 100,000 | Columns: 20 
Description: E-commerce order-level data containing customer, product, category, pricing, discount, payment, order 
status and geographic information. 
Why selected: Large dataset with multiple business dimensions for meaningful sales analysis. 
Opportunities: Identify top categories/products, geographic performance, discount impact, payment trends and order
status improvement opportunities. 
# Q2. Business Problem, Questions & Hypotheses 
Business Problem: Understand key drivers of e-commerce sales and identify products, categories, markets and 
operational areas where management can improve performance. 
Questions: Which categories generate the highest sales? Which countries and cities contribute most? Which products 
and brands perform best? Which payment methods are most used? How do discounts affect sales and profit proxy? 
H1: Electronics will generate the highest category sales. 
H2: Higher discounts will be associated with lower profit proxy. 
# Q3. Data Cleaning 
Missing Values: Checked all columns; 0 missing values found. 
Duplicates: Checked records; 0 duplicates found. 
Data Types: Converted OrderDate to date and numeric columns to numeric format. 
Standardization: Checked Category, Brand, PaymentMethod, OrderStatus and Country for consistency. 
Calculated Fields: Created GrossSales, DiscountAmount, NetSales, Month, Year and ProfitProxy. 
Outliers: Reviewed Quantity, UnitPrice and TotalAmount for unusual values. 
# Q4. Key Insights 
Electronics generated the highest sales among categories. 
United States generated the highest sales among countries. 
Credit Card had the highest number of orders and sales among payment methods. 
Most orders were Delivered, with fewer Cancelled or Returned. 
No-discount orders generated the highest sales and profit contribution. 
# Q5. Hypothesis Reflection 
Expected: Higher discounts would increase sales and order volume. 
Actual: No-discount orders generated the highest sales and profit contribution compared with higher-discount groups. 
Reason: Demand may already be sufficient for many products; the dataset does not prove the exact reason. 
Analysis: Compared sales and profit proxy across discount groups. 
Conclusion: Higher discounts do not automatically improve sales; use targeted discounts. 
# Q6. Data Quality & Limitations 
Missing values: 0 found. Duplicates: 0 found. 
Missing cost data: Actual product and marketing costs are unavailable, so ProfitProxy was used instead of claiming 
actual profit. 
Limitations: Dataset may not represent current market conditions; actual product and marketing costs are unavailable. 
Cannot safely conclude that discounts directly cause lower profit because the dataset cannot prove causation. 
# Q7. Recommendations 
1. Focus on top categories: Increase inventory and marketing for high-sales categories. 
2. Optimize discounts: Use targeted discounts instead of broad discounts. 
3. Reduce cancellations: Identify and fix major cancellation reasons. 
# Q8. Dashboard Plan 
Dashboard: Amazon E-Commerce Sales & Performance Dashboard. 
Purpose: Overview of sales, customers, category performance, geographic performance and order status. 
Visualizations: Total Sales KPI; Total Orders KPI; Sales by Category; Sales by Geography; Monthly Sales Trend; Order 
Status. 
# Q9. Presentation Outline 
1. Business Problem — Analyze e-commerce sales, products, categories and markets. 
2. Data & Methodology — 100,000 records, 20 columns; Python and Pandas. 
3. Key Findings — Electronics leads; United States largest market; Credit Card most-used; most orders delivered. 
4. Deep-Dive — No-discount orders had highest sales and profit contribution. 
5. Recommendations — Focus categories, optimize discounts, reduce cancellations. 
6. Impact — Higher revenue, profitability and order completion. 
7. Limitations — Costs unavailable; ProfitProxy is not accounting profit. 
# Q10. AI Usage 
AI Tool: ChatGPT. 
Used for: Dataset understanding, Python code, debugging, analysis ideas and documentation. 
Example: Helped create data-cleaning and analysis code.
