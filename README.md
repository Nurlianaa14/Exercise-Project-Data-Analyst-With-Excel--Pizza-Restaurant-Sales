# Exercise-Project-Data-Analyst-With-Excel--Pizza-Restaurant-Sales

## Dataset: 
  Data from https://www.mavenanalytics.io/blog/maven-pizza-challenge
  
  Open Source in Kaggle https://www.kaggle.com/datasets/shilongzhuang/pizza-sales

## Contents:

This pizza sales dataset make up 12 relevant features:

- order_id: Unique identifier for each order placed by a table
- order_details_id: Unique identifier for each pizza placed within each order (pizzas of the same type and size are kept in the same row, and the quantity increases)
- pizza_id: Unique key identifier that ties the pizza ordered to its details, like size and price
- quantity: Quantity ordered for each pizza of the same type and size
- order_date: Date the order was placed (entered into the system prior to cooking & serving)
- order_time: Time the order was placed (entered into the system prior to cooking & serving)
- unit_price: Price of the pizza in USD
- total_price: unit_price * quantity
- pizza_size: Size of the pizza (Small, Medium, Large, X Large, or XX Large)
- pizza_type: Unique key identifier that ties the pizza ordered to its details, like size and price
- pizza_ingredients: ingredients used in the pizza as shown in the menu (they all include Mozzarella Cheese, even if not specified; and they all include Tomato Sauce, unless another sauce is specified)
- pizza_name: Name of the pizza as shown in the menu

## The Pizza Challenge

For the Maven Pizza Challenge, you’ll be playing the role of a BI Consultant hired by Plato's Pizza, a Greek-inspired pizza place in New Jersey. You've been hired to help the restaurant use data to improve operations, and just received the following note:

Welcome aboard, we're glad you're here to help! 

Things are going OK here at Plato's, but there's room for improvement. We've been collecting transactional data for the past year, but really haven't been able to put it to good use. Hoping you can analyze the data and put together a report to help us find opportunities to drive more sales and work more efficiently.

Here are some questions that we'd like to be able to answer:

1. What days and times do we tend to be busiest?
2. How many pizzas are we making during peak periods?
3. What are our best and worst-selling pizzas?
4. What's our average order value?
5. How well are we utilizing our seating capacity? (we have 15 tables and 60 seats)

That's all I can think of for now, but if you have any other ideas I'd love to hear them – you're the expert!

Thanks in advance,

Mario Maven (Manager, Plato's Pizza)
