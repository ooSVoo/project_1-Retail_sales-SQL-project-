
# Project 1 – Retail Sales Analysis

Level – Beginner

Database – p1_retail_db

This project presents a comprehensive analysis of retail sales data, showcasing SQL techniques crucial for data analysts. The objective is to establish a structured database, ensure data integrity through cleaning processes, perform exploratory data analysis (EDA), and derive meaningful business insights via SQL queries. This approach aims to support strategic decision-making and optimize business performance.


# Objective:
1.	**Database Setup:** Create and populate a retail sales database with provided sales data.
2.	**Data Cleaning:** Identify and handle missing, null, or duplicate records to ensure data accuracy and integrity.
3.	**Exploratory Data Analysis:** Use SQL queries to explore the dataset, uncover trends, and understand sales patterns.
4.	**Business Analysis:** Answer specific business questions and extract actionable insights through SQL queries.

## Project Structure

1. **Database Setup :**

* Database Creation : Initiate the project by creating a database named __retail_project1__
* Table Creation : A table named retail_sales is created to store the sales data. The table structure includes:

    * transaction_id (PRIMARY KEY)
    * sale_date , sale_time
    * customer_id , gender , age
    * product_category , quantity_sold , price_per_unit , COGS , sale_amount

![image](https://github.com/user-attachments/assets/844a3284-ed03-44e5-ab0e-2dd704f4393b)

2. **Data Exploration and Cleaning :**

    * Record Count : Calculate the total number of records in the dataset.
    * Customer Count : Count the unique customers in the dataset
    * Category Count : List all the unique prodct categories
    * Null Value Check : Identify and delete records with missing data to ensure clean, usable information
