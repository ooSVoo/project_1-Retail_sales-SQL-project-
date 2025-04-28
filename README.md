
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
    * Duplicate Record Check : Identify and remove duplicate transactios to prevent inflated sales or skewed insights.
    * Outlier Detection : Check for unusually high or low values in quantities_sold, price_per_unit or sale_amount to catch potential data enetry errors.
    * Date Range Validation : Nesure that sales dates are within the expected period and there are no erroneous futuer / past dates.
![image](https://github.com/user-attachments/assets/9e407149-a966-4d08-96b5-e2b2351989da)


3. **Data Analysis and Findings :**
    
    The following SQL queries were developed to answer specific business questions:
    
    #### **Sales on a Specific Date :**
    
    • **Business Impact:** To Understand sales on specific dates helps track the           effectiveness of promotions, events and seasonal spikes. This insight is crucial for inventory planning and marketing.

    ![Image](https://github.com/user-attachments/assets/e862caee-d424-4db0-a38a-2ea184378aad)

    #### **Category-Based Sales**
    
    • **Business Impact:** Understanding category – level revenue helps businesses allocate marketing budgets effectively, prioritize high performing products, and phase out underperforming categories. This insight also aids in negotiating with suppliers for bulk discounts on best-selling items
    ![Image](https://github.com/user-attachments/assets/88bef46f-378a-4dd1-8bf5-20e506153720)
    
    #### **Category-Wise Total Sales :**
    **• Business Impact:** Knowing which product categories and quantities sell on certain dates helps refine inventory management and targeted maketing strategies. For example, if clothing sales spike in large quantities during the holiday season, businesses can stock up accordingly, preventing stockouts and maximizing revenue

    ![Image](https://github.com/user-attachments/assets/7f73db73-a501-4fa6-80a6-429fbc709634)
    
    #### **Average Age of Customers by Category :**
    **• Business Impact:** Knowing the average age of customers for each category helps businesses refine their target audience, create more personalized marketing campaigns, and even adjust product offerings to better suit consumer demographics.
    
    ![Image](https://github.com/user-attachments/assets/95fe261f-3784-4d59-b578-e92c24204439)
