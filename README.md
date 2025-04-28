
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

   #### **High-Value Transactions :**
    **• Business Impact:** Identifying transactions with high total sales helps businesses understand big spenders, which can inform loyalty programs or VIP marketing strategies. Additionally, it can reveal which products contribute the most to revenue, guiding future product development or promotional efforts.

    ![Image](https://github.com/user-attachments/assets/819de370-1680-4f39-b36c-cdfe3987e491)

    #### **Transactions by Gender and Category :**
    **• Business Impact:** Analyzing purchase behavior across gender and product categories helps businesses tailor marketing strategies, product placement, and promotions to different demographics. For instance, if women make more purchases in the beauty category, campaigns can be customized for that audience.

    ![Image](https://github.com/user-attachments/assets/4ac90e6d-3941-4fa9-9daf-bf97dde827cb)

    #### **Monthly Average Sales and Best-Selling Months :**
    **• Business Impact:** Understanding monthly sales trends helps businesses plan seasonal promotions, budget for inventory, and manage supply chains. Identifying the best-performing months also enables strategic planning for flash sales or new product launches.

    ![Image](https://github.com/user-attachments/assets/d3bf5613-b458-4ebf-93e3-c4bddbd7922c)

    #### **Top 5 Customers by Total Sales.**
    **• Business Impact:** Identifying the top 5 customers with the highest total sales is critical for customer relationship management (CRM) and targeted marketing. These high-value customers contribute significantly to overall revenue, and nurturing them through loyalty programs, personalized offers, and exclusive promotions can enhance customer retention and lifetime value. Understanding who these customers are enables businesses to craft specialized strategies to encourage repeat purchases and turn them into brand advocates.

    ![Image](https://github.com/user-attachments/assets/e960fe4f-60a3-42f2-b7b9-bcf811956162)

    #### **Unique Customers per Product Category :**
    **• Business Impact:** Understanding the number of unique customers purchasing from each category helps in evaluating category-specific customer reach and appeal. This insight can inform product assortment decisions, guide targeted marketing campaigns, and reveal opportunities to grow customer bases in underperforming categories. For example, if the "Beauty" category has fewer unique customers, promotional efforts or bundle deals could attract more buyers. This data is valuable for balancing inventory, refining category offerings, and tailoring customer engagement strategies.

    ![Image](https://github.com/user-attachments/assets/52324ee7-ed64-460c-8297-3c742fe60534)

    #### **Order Distribution by Shift :**
    **• Business Impact:** Understanding when sales peak during the day helps optimize staffing, inventory replenishment, and marketing efforts. By categorizing transactions into shifts — morning, afternoon, and evening — businesses can align operations with customer behavior. For instance, if most sales happen in the evening, the store can allocate more staff, run evening-specific promotions, or ensure popular products are well-stocked. Similarly, identifying slow periods allows for strategic downtime activities, like restocking shelves or conducting team meetings, to enhance overall efficiency and customer satisfaction.

    ![Image](https://github.com/user-attachments/assets/ba9f6673-3327-4561-bfbf-d3d671ca97f8)

    #### **Total Revenue Generated by each Customer :**
    **• Business Impact:** Knowing the total revenue generated by each customer helps businesses identify high-value clients, prioritize customer retention strategies, and personalize marketing efforts. For example, customers with the highest lifetime value might be targeted with exclusive offers or loyalty programs to encourage repeat purchases. Conversely, understanding lower-spending customers can help tailor budget-friendly promotions or product recommendations to increase their engagement and spending. This insight is invaluable for segmenting customers and crafting more effective, data-driven business strategies.

    ![Image](https://github.com/user-attachments/assets/7fd29a26-db15-4e8f-9463-7b5ec4c714ed)

    #### **Number of transactions per Age Group :**
    **• Business Impact:** Analyzing transactions by age group helps businesses tailor product offerings, promotions, and marketing campaigns to specific demographics. For instance, if younger customers make more frequent purchases, the business can focus on social media advertising or trendy product categories. On the other hand, if older age groups contribute fewer but higher-value transactions, targeted loyalty programs or exclusive discounts might be more effective. This segmentation empowers data-driven decisions to enhance customer engagement and boost sales.

    ![Image](https://github.com/user-attachments/assets/548d83ea-f27f-45d9-831d-db46cd677216)

    #### **Category-Wise Profit Management :**
    **• Business Impact:** Understanding the profit margin for each product category helps businesses identify their most and least profitable segments. This insight is crucial for pricing strategies, supplier negotiations, and marketing efforts. For instance, if certain categories have low margins but high sales volume, the business might consider bulk purchasing discounts or streamlining supply chains. Conversely, categories with high margins could benefit from increased promotional efforts to maximize revenue. Tracking this metric enables businesses to optimize profitability and make data-driven decisions for sustainable growth.

    ![Image](https://github.com/user-attachments/assets/aed1db2e-0afc-48d8-a3b7-3e99cdf3caea)

    #### **Identify peak sales hours :**
    **• Business Impact :** Knowing the peak sales hours is essential for resource allocation, staffing, and promotional timing. If a business experiences a surge in sales during specific time windows, it can optimize operations by scheduling more staff, running targeted promotions, and ensuring inventory availability. For example, a retail store might discover that evenings are the busiest period, prompting them to extend store hours or offer time-limited discounts to capitalize on the high foot traffic. Understanding sales patterns helps in enhancing customer service and maximizing revenue during high-demand periods.

    ![Image](https://github.com/user-attachments/assets/deb6b424-b4d4-4dbf-bed2-807563208b2d)

    #### **Identify Fastest Selling Products :**
    **• Business Impact:** Identifying the fastest-selling products helps businesses manage inventory, streamline supply chains, and prioritize marketing efforts. Products with high turnover rates are valuable indicators of consumer demand, enabling businesses to prevent stockouts and capitalize on popular trends. For example, if a particular product sells rapidly during a specific season, the business can pre-stock and run targeted promotions to amplify sales. This insight also aids in negotiating with suppliers for better pricing or bulk discounts, directly impacting profitability.

    ![Image](https://github.com/user-attachments/assets/a6a4347f-35de-4dc1-986b-a497513edd99)
