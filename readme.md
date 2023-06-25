## A Restaurant Database Development and Analysis Project

### INTRODUCTION
An end-to-end project to address the increasing demand for online services and the growing number of orders at a restaurant.
As part of this project, comprehensive data analysis will be conducted to gain valuable insights from the existing customer data.      
It involves examining various aspects, such as customer demographics, sales trends, order patterns, and preferences.

### PROBLEM STATEMENT
The restaurant currently stores its data in a spreadsheet. With the inclusion of online bookings and orders, there is a need to migrate the data to a database management system. This migration is necessary to efficiently streamline operations and accommodate the growing number of customers and online services.

                                                                                                                 
### DATABASE DEVELOPMENT AND TESTING


![database_model](https://github.com/TheDataCode/Database-Capstone-Project/blob/main/lemon_db_schema.png)






- ### Database Schema                                             
    [Schema Script](https://github.com/TheDataCode/Database-Capstone-Project/blob/main/little_restaurant_db.sql)


- ### Data Insertions
    [Insert Statements](https://github.com/TheDataCode/Database-Engineering-and-Analysis-Project/blob/main/insert_script.sql)  
    

- ### Stored Procedures
   #### Created stored procedures for efficient data manipulation 
    [Data Insertion](https://github.com/TheDataCode/Database-Capstone-Project/blob/main/storedprocedure_insertions.sql)              
    [Select Maximum Order](https://github.com/TheDataCode/Database-Capstone-Project/blob/main/stored_procedures.sql)                  
    [Booking Verification](https://github.com/TheDataCode/Database-Capstone-Project/blob/main/storedProcedure-checkBooking.sql)       
    [Update Booking](https://github.com/TheDataCode/Database-Capstone-Project/blob/main/storedProcedure-Updates.sql)                  
    [Cancel Orders](https://github.com/TheDataCode/Database-Capstone-Project/blob/main/storedProcedure-Delete_statement.sql) 
    
    #### Data Manipulation using Stored Procedures and Transactions.                                                                                      
    Data manipulation with stored procedures and transactions in databases provide a structured and controlled approach to database operations, ensuring data integrity, consistency, and security while promoting code reusability and performance optimisation.
    
    [Data Validation using Stored Procedures Transactions](https://github.com/TheDataCode/Database-Engineering-and-Analysis-Project/blob/a75dde793ce212761858a880ee23074d98096bc7/Stored%20Procedure%20with%20Transactions.sql)                                                                       
    
 - ### View, Subquery and Join
     [View, Subquery and Join ](https://github.com/TheDataCode/Database-Capstone-Project/blob/main/data_retrieval_scripts.sql)


 - ### Prepared Statement
    prepared statements in MySQL offer performance optimisation, protection against SQL injection attacks, increased security, improved       code maintainability, readability, and database portability. They are essential for building secure, efficient, and            maintainable database-driven applications.                                                                                                                                                                                                                                         
      
      [Query Data with Prepared Statement](https://github.com/TheDataCode/Database-Capstone-Project/blob/main/prepared_statement.sql)
     
     
 - ### MySQL/Python Connector
      [Query Data Using MySQL/Python Connector](https://github.com/TheDataCode/Database-Capstone-Project/blob/main/data-retrieval-with-python.ipynb) <br><br><br><br><br>

### DATA ANALYSIS 
Comprehensive data analysis to gain valuable insights from the existing customer data. It involves various aspects, such as sales trends, customer demographics, top-performing customers, order patterns, and preferences. 
  #### Concepts Applied In Tableau
   - Calculated Fields
   - Actions
   - Objects
   - Filters
     
View customer analysis report on [tableau public](https://public.tableau.com/views/RestaurantSalesPerformance/RestaurantSalesPerformance?:language=en-US&:display_count=n&:origin=viz_share_link) <br><br>
![Restaurant Sales Performance](https://github.com/TheDataCode/Database-Engineering-and-Analysis-Project/assets/107037322/8c486e99-4129-4097-8dbf-c97c08921968)


