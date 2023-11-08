# Restraunt-Database
# Restaurant Management System Database

This repository contains the database schema and SQL queries for a fictional restaurant management system. The database is designed to handle various aspects of restaurant operations, including customer orders, menu items, employee management, vendor relationships, and more.

## Database Schema

The restaurant management system's database is organized into several tables, each serving a specific purpose. Here is a brief overview of the key tables and their descriptions:

1. `ORDERS`: Stores information about customer orders, including order ID, customer ID, payment type, date, and rating.

2. `ITEMS_ORDERED`: Records items ordered within each order, along with their item ID, price, and size.

3. `JOBS`: Manages job positions within the restaurant, including job ID, job description, and salary.

4. `POSITIONS`: Tracks employee positions, including position ID, supervisor ID, and position description, with a reference to job positions.

5. `INGREDIENTS`: Stores information about ingredients used in the restaurant, such as ingredient ID, description, quantity on hand, and vendor ID.

6. `DIPLOMA`: Records employee diplomas and certifications.

7. `MNGR_DIPLOMA`: Associates employees with their diplomas and certifications.

8. `ITEMS_HISTORY`: Keeps track of historical item prices over time.

9. `CURR_SUPERVISOR`: Associates employees with their current supervisors and job positions.

10. `INGR_USED`: Tracks the use of ingredients in menu items.

11. `POINTS_CAPTURED`: Records points captured from customers.

12. `STATUS`: Manages order statuses.

13. `ORDER_STATUS`: Associates order statuses with specific orders.

14. `CHEF`: Contains information about chefs.

15. `CHEF_CERTIFIED`: Associates employees with their chef certifications.

16. `C_W_PGCARD`: Manages customer reward cards.

17. `SUB-FAMILY`: Organizes menu item sub-families.

18. `NON_FOOD_SUPPLIES`: Tracks non-food supplies.

19. `SHIFT`: Manages work shifts.

20. `MANAGER`: Stores employee IDs for individuals in managerial roles.

21. `CHEF_CERT`: Records chef certifications.

22. `VENDORS`: Manages vendor information.

23. `CUSTOMER`: Stores customer information.

## SQL Queries
These queries typically involve operations such as selecting data from tables, inserting new records, updating existing records, and joining tables to retrieve related information.

The SQL queries will be tailored to the needs of the restaurant management system, enabling interactions with the database to manage orders, employees, menu items, and more.
