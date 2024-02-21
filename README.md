# ChemLabCo
managing the database for "ChemLabCo," a company that supplies chemicals and laboratory equipment to various institutions and research facilities around the world

Background:
You are managing the database for "ChemLabCo," a company that supplies chemicals and laboratory equipment to various institutions and research facilities around the world. The company keeps track of suppliers, orders, and the products (chemicals, equipment, etc.) it offers. Your task is to organize, update, and retrieve information from the database to support the company's operations.

Database Setup:
1.  Create Tables : Start by creating the necessary tables for the company. Assume the following structures:
    - Suppliers : Contains information about suppliers.
    -  Orders : Contains details of orders placed by institutions.
    - Products : Contains information about chemicals and laboratory equipment offered by the company.

2.  Insert Data: Populate the tables with initial data. Assume some suppliers are from Germany, some products have been ordered, and various chemicals and equipment are available.

 Exercises :
 Basic Data Manipulation and Retrieval
1. Insert New Suppliers: Add new suppliers to the `Suppliers` table, including their names, addresses, and countries.
2. Select All Suppliers: Retrieve all supplier records from the `Suppliers` table.
3. Find Unique Cities: List all distinct cities where the company's suppliers are located.
4. Order Details Insertion: Insert multiple records into the `Orders` table in a single statement.

Filtering and Sorting
5. Suppliers from a Specific Country: Retrieve all suppliers from the United States.
6. German Suppliers Sorted: List all suppliers from Germany, ordered by their names in both ascending and descending order.
7. Suppliers with Names Starting with 'K': Find all suppliers from Germany whose names start with 'S'.

Advanced Queries and Aggregations
8. Correcting Country Names: Update the country name from 'Germnay' to 'Germany' for all affected suppliers.
9. Deleting Records: Remove a supplier from the database based on their supplier ID.
10. Limiting Results: For systems that support it, retrieve the top 3 suppliers added to the database.
11. Aggregations: Calculate the minimum, maximum, and average values for certain fields in the `Orders` and `Products` tables, such as the minimum and maximum quantity of products ordered and the average price of a specific product.

Grouping and Counting
12. Counting Distinct Countries and Prices: Determine the number of distinct countries represented in the `Suppliers` table and the number of distinct prices in the `Products` table.
13. Products Count by City: Count the number of products available in each city and list them.

 Advanced Exercises:
14. Sum and Average Calculations: Calculate the total quantity of products ordered for a specific city and the average price of a particular product.
15. Grouping Products by City: Group the products by city and count the number of products in each city.


Sample Data Insertion:

- Suppliers:
```sql
INSERT INTO Suppliers VALUES
(1, 'ChemSupply GmbH', 'Berlin', 'Germany'),
(2, 'LabEquip Co', 'Munich', 'Germany'),
(3, 'ReagentExpress', 'San Francisco', 'USA');
```

- Products:
```sql
INSERT INTO Products VALUES
(1, 'Sodium Chloride', 50, 'Chemical', 'Berlin'),
(2, 'Erlenmeyer Flask', 150, 'Equipment', 'Munich'),
(3, 'Bunsen Burner', 75, 'Equipment', 'San Francisco');
```

- Orders:
```sql
INSERT INTO Orders VALUES
(1, 1, 1, 10),
(2, 2, 2, 5),
(3, 3, 3, 15);
```

This exercise encompasses a range of SQL operations, from basic data insertion and retrieval to more complex filtering, sorting, and aggregation tasks, tailored to a chemical laboratory supply scenario.
