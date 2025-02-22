# Ecommerce-Power-BI-dashboard

### Dashboard Link: [https://app.powerbi.com/links/F4UVC2uSk9?ctid=84c31ca0-ac3b-4eae-ad11-519d80233e6f&pbi_source=linkShare]

### Dasboard Snapshot: [![Image](https://github.com/user-attachments/assets/56205721-c173-4156-95fa-e37b7734e36e)]

# Problem Statement
This interactive Power BI dashboard provides a comprehensive eCommerce sales analysis, enabling businesses to track sales performance, identify trends, and optimize their strategies. It provides insights into monthly sales trends, quarterly performance, sales by cities and states, total revenue, profit, quantity sold, and customer behaviour.

By leveraging these insights, businesses can identify top-performing products, understand customer purchasing patterns, and optimize marketing and inventory strategies to maximize profits.

## Key Insights

        •	Total Sales Trends analysed across all 12 months.

        •	Quarterly Sales Performance breakdown (Q1-Q4).

        •	Sales Distribution by Cities & States to understand regional demand.

        •	Total Revenue, Profit & Quantity Sold for a holistic business overview.

        •	Profit Breakdown by Sub-Categories to identify the most and least profitable products.

        •	Quantity Sold by Product Categories to track demand fluctuations.

        •	Payment Mode Analysis (Credit Card, Debit Card, UPI, COD) to understand customer payment preferences.

        •	Top Customers & Their Purchase Amounts to recognize high-value customers and enhance customer retention strategies.

## Steps Followed

# Data Preparation

•	Step 1: Loaded the dataset (CSV file) into Power BI Desktop.

•	Step 2: Used Power Query Editor for data cleaning and transformation.

•	Step 3: Checked "Column Distribution," "Column Quality," and "Column Profile" options to identify data inconsistencies.

•	Step 4: Removed null values and ensured data integrity, especially for sales and profit fields.

# Data Visualization & Analysis
•	Step 5: Applied theme settings for a visually appealing dashboard.

•	Step 6: Created interactive slicers for "Product Category," "Payment Mode," "Customer Type," and "Region."

•	Step 7: Added card visuals to display key metrics: 
                  o Total Revenue
	                o Total Profit
	                o Total Quantity Sold

•	Step 8: Designed a bar chart to represent monthly and quarterly sales trends.

•	Step 9: Created a map visualization to showcase sales distribution by state and city.

•	Step 10: Implemented doughnut and pie charts to analyse payment mode preferences and product category performance.

•	Step 11: Developed a customer segmentation analysis by calculating sales contribution by top customers.

•	Step 12: Created calculated columns and measures using DAX expressions for advanced insights: 
              
                o	Profit Margin Calculation: 
                o	Profit Margin = (SUM(Sales[Profit]) / SUM(Sales[Total Sales])) * 100
                o	Customer Contribution Percentage: 
                o	Customer Contribution = (DIVIDE(SUM(Sales[Total Sales]), CALCULATE(SUM(Sales[Total Sales]), ALL(Sales[Customer Name])))) * 100
                o	Total Sales by Product Category: 
                o	Total Sales by Category = SUM(Sales[Total Sales])

•	Step 13: Published the report to Power BI Service for real-time access and sharing.

## Insights & Recommendations

1. Sales Performance
  
        •	Highest sales recorded in Q4, indicating increased demand during holiday seasons.

        •	The lowest sales occurred in Q2, highlighting an opportunity for promotional campaigns.

2. Product & Profitability Analysis

        •	The top three most profitable product sub-categories: 

        1.	Electronics
        2.	Fashion
        3.	Home & Kitchen
        •	Certain sub-categories showed lower profit margins, requiring pricing strategy adjustments.

3. Customer Behavior

        •	Returning customers contributed 65% of total sales, indicating strong customer loyalty.
        •	High-value customers (top 10%) contributed nearly 40% of total revenue, emphasizing the need for VIP customer retention programs.

4. Regional Sales Distribution
        
        •	Top-performing states: 
        o	UP
        o	Andhra Pradesh
        o	Delhi
        •	Some states showed lower sales, indicating potential markets for expansion.

5. Payment Mode Preferences

        •	Credit Card transactions accounted for 55% of total sales, making it the most preferred payment method.
        •	Cash-on-Delivery (COD) usage was higher in specific regions, requiring logistic optimizations.

6. Operational Efficiency

        •	The analysis identified delays in order fulfillment in specific regions, suggesting an opportunity to improve the supply chain.
        •	Products with high return rates were analysed to improve product descriptions and customer expectations.

# Conclusion
This Power BI dashboard provides a data-driven approach to optimize sales strategies, enhance customer satisfaction, and maximize profitability. Businesses can use these insights to improve their marketing efforts, adjust pricing strategies, and refine customer engagement tactics for sustainable growth.

Let me know your thoughts on this dashboard! How do you analyse your sales data? 🚀
