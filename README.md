# Credit-Card-Financial-Report-Analytics
This project delivers an in-depth Power BI analysis of Credit Card Financial Data, with interactive dashboards for visualizing customer and transaction trends. It is designed to offer business insights that drive strategic decisions.

Problem Statement:
In this project, we aimed to build two dashboards that provide in-depth analysis of:
Credit Card Customers – Analyzing customer demographics and their credit card ownership.
Credit Card Transactions – Investigating transaction data, including spending categories and transaction frequency.

Key Goals:
Create interactive dashboards filtered by gender, age group, and income group.
Provide insights into spending patterns and transaction trends.
Offer visualizations that can help stakeholders make data-driven decisions.

Data Dictionary 🗃️
Customer Data:
customer_id: Unique identifier for each customer.
gender: Male/Female.
age: Age of the customer.
income: Income of the customer.
credit_score: Credit score of the customer.
ownership_status: Whether the customer owns the credit card or not.
Transaction Data:
transaction_id: Unique identifier for each transaction.
transaction_date: Date of the transaction.
transaction_amount: Amount spent in the transaction.
transaction_category: Category of spending (e.g., Food, Electronics).
transaction_type: Type of transaction (e.g., Purchase, Payment).
customer_id: Linked to the customer who made the transaction.

Insights 💡
Customer Demographics:
60% of the customer base is male, with males having a higher average income than females.
The 26-35 age group comprises 40% of the total customers, making it a key target group.

Spending Categories:
Food and Electronics are the most popular spending categories, contributing to 30% of the total spending.
Male customers have 25% higher transaction volume compared to females, particularly in electronics.

Transaction Frequency:
Males tend to make more frequent transactions than females, with a 20% higher frequency of spending in retail and electronics.

Revenue Trends:
Weekly revenue has been growing consistently, with a 10% increase week-over-week, mainly driven by high-value transactions in electronics and retail.

DAX Calculations 🔢
To enhance the interactivity and functionality of the dashboards, the following DAX calculations were used:
Age Group Calculation:
Categorizing customers into age groups (e.g., 18-25, 26-35, etc.) to filter the dashboard by age.
Income Group Calculation:
Using DAX to categorize customers as Low, Medium, or High income groups based on predefined thresholds.
Total Revenue:
Calculating the total revenue for each customer segment and week using DAX measures.
Weekly Revenue Comparison:
Calculating current week revenue and previous week revenue to track the growth in sales and performance.

Conclusions & Recommendations 🔍
Focus on High-Value Customers:
Target medium-income groups, who contribute to 55% of the total revenue. Tailor offers to this segment to drive further engagement.
Expand High-Revenue Categories:
Given the growth in electronics and food spending, consider expanding product offerings or promotions in these categories.
Gender-Specific Marketing:
Target male customers more actively, especially in electronics, where they spend significantly more.
Monitor Weekly Trends:
Keep tracking weekly revenue patterns and adjust marketing strategies based on the data.



