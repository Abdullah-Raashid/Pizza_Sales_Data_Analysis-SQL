# Pizza Sales Data Analysis with SQL

This project analyzes pizza sales data using SQL queries to extract key business insights, such as order trends, revenue distribution, and top-selling pizzas.

## Features

- **Basic Queries**
  - Total number of orders placed
  - Total revenue from pizza sales
  - Most expensive pizza
  - Most common pizza size ordered
  - Top 5 most ordered pizza types  

- **Intermediate Queries**
  - Total quantity of each pizza category ordered
  - Order distribution by hour
  - Average number of pizzas ordered per day
  - Top 3 pizza types based on revenue  

- **Advanced Queries**
  - Percentage contribution of each pizza type to total revenue
  - Cumulative revenue over time
  - Top 3 most ordered pizzas per category based on revenue  

## Dataset & Schema

The queries work on a relational database with tables such as:
- `orders` – Stores order details (order_id, order_date, order_time)
- `order_details` – Contains quantity and pizza_id for each order
- `pizzas` – Lists pizza types, sizes, and prices
- `pizza_types` – Defines pizza names and categories  

## 🛠️ How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pizza-sales-analysis.git

2. Import the dataset into a SQL database.
3. Run the queries in an SQL environment such as MySQL, PostgreSQL, or SQLite.
4. Modify and expand the queries as needed for deeper insights.
