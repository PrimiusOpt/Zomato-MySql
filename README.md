# Zomato-MySql
A MySQL-based Zomato-like database project for restaurant management, including users, restaurants, menu items, orders, and reviews. It demonstrates relational database design, foreign key constraints, and SQL queries like retrieving average ratings, orders, and reviews. Ideal for learning SQL.

# Zomato Database Project

This is a MySQL-based database project that simulates a **Zomato-like** restaurant review and ordering system. It includes tables for **Users**, **Restaurants**, **Menu Items**, **Orders**, **Order Items**, and **Reviews**. This project demonstrates relational database design and SQL queries.

## Features

- **Users Table**: Stores user details (username, email, phone, address).
- **Restaurants Table**: Stores restaurant information (name, location, cuisine, contact).
- **Menu Items Table**: Stores menu items for each restaurant (name, price, description).
- **Orders Table**: Tracks customer orders with status and total price.
- **Order Items Table**: Manages items in an order, with a many-to-many relationship between Orders and Menu Items.
- **Reviews Table**: Stores user reviews for restaurants, including ratings and comments.

## Setup Instructions

1. **Create the Database**:
    ```sql
    CREATE DATABASE zomato;
    USE zomato;
    ```

2. **Create Tables**:
    Execute the SQL statements provided to create the **Users**, **Restaurants**, **Menu Items**, **Orders**, **Order Items**, and **Reviews** tables.

3. **Insert Sample Data**:
    Sample data is included in the project to test the database functionality. You can insert the sample data into the respective tables using the provided `INSERT` statements.

4. **Run Queries**:
    The project includes various SQL queries to interact with the database, such as:
    - Get all restaurants and their average ratings.
    - Retrieve menu items for a specific restaurant.
    - Get all orders by a user.
    - Display reviews for a restaurant.
    - Calculate total earnings for each restaurant.

## Technologies Used

- **MySQL**: For creating and managing the database.
- **SQL**: For writing and executing queries to interact with the database.

## License

This project is for learning purposes. Feel free to fork and modify it as needed.

---

**Note**: Adjust any sections based on your specific needs or additional content.
