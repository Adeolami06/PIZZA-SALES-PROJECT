# PIZZA-SALES-PROJECT
comprehensive analysis of its Pizza Sales Data for the year 2015
Metadata for Pizza Sales Data (2015)
Dataset Overview
As part of the ongoing efforts to optimize sales performance, improve menu offerings, and enhance customer experience, this food outlet requires a structured analysis of the Pizza Sales Data (2015). The dataset contains transactional details, including order volume, pricing, pizza categories, and timestamps.
The MetaData is as follows:
•	pizza_id: Unique identifier for each pizza.
•	order_id: Unique identifier for each pizza order. Multiple pizzas can belong to the same order, as indicated by sharing the same order_id.
•	pizza_name_id: Identifier for the specific type or name of the pizza. This may be linked to a separate table that contains details about each pizza type.
•	quantity: The number of pizzas of a specific type in a given order.
•	order_date: The date when the order was placed.
•	order_time: The time when the order was placed.
•	unit_price: The price of a single pizza unit.
•	total_price: The total price for the quantity of pizzas in a specific order. It is calculated as the product of quantity and unit_price.
•	pizza_size: The size of the pizza (e.g., S for Small, M for Medium, L for Large).
•	pizza_category: The category or type of pizza (e.g., Classic, Veggie, Chicken, Supreme).
•	pizza_ingredients: A list of ingredients that make up the pizza. This column provides information about the toppings or components of each pizza.
•	pizza_name: The name or label of the pizza. It is likely a human-readable identifier for the type of pizza, corresponding to the pizza_name_id.

REQUIRED INSIGHTS:
1. Sales Performance & Revenue Analysis
•	Total Revenue: What is the total revenue generated in 2015?
•	Monthly Revenue Trends: How do sales fluctuate across different months? Are there any seasonal patterns?
•	Daily & Hourly Sales Distribution: What are the peak sales days and times?
•	Average Order Value (AOV): What is the average revenue per order?
2. Product Performance & Menu Optimization
•	Top & Bottom-Selling Pizzas: Which pizza types are the most and least popular based on quantity sold?
•	Revenue by Pizza Category: How does sales performance vary across different categories (e.g., Vegetarian, Non-Vegetarian, Vegan)?
•	Revenue by Pizza Size: What proportion of sales comes from small, medium, and large pizzas?
3. Customer & Order Behaviour
•	Average Quantity per Order: How many pizzas are typically ordered in a transaction?
•	Most Common Order Time: At what time of the day are most orders placed?
•	Day of the Week Analysis: Which days have the highest and lowest sales volumes?
4. Pricing & Discount Strategy
•	Price Sensitivity: Do higher-priced pizzas sell less compared to lower-priced ones?
•	High-Value vs. Low-Value Orders: What percentage of orders contribute the most revenue?
•	Seasonal Pricing Effects: Are there opportunities for seasonal promotions based on demand trends?
5. Ingredient & Inventory Optimization
•	Most Used Ingredients: Which ingredients are in highest demand based on sales?
•	Cost vs. Revenue Analysis: How do ingredient costs compare to revenue generated per pizza type?
6. Operational Efficiency & Order Fulfillment
•	Order Processing Time: If timestamps are available, what is the average time between order placement and fulfillment?
•	Delivery vs. Dine-in Sales (if applicable): How do sales compare across different service channels?
