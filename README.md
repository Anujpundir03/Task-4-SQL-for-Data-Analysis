# Bookstore SQL Data Analysis

This project addresses **Task 4: SQL for Data Analysis** by using SQL queries to analyze a simulated bookstore transaction dataset.

## 📁 Dataset

The analysis is based on three simulated CSV files:
1.  **`Customers.csv`**: Contains customer demographics (ID, Name, Country).
2.  **`Books.csv`**: Contains book inventory details (ID, Title, Price, Genre).
3.  **`Orders.csv`**: Contains transactional data (Order ID, Customer ID, Book ID, Total Amount).

These files are located in the [`data/`](./data) directory.

## 🛠️ Tools Used

* **Database:** SQLite / MySQL / PostgreSQL (Any relational database)
* **Language:** SQL (Structured Query Language)

## 🚀 How to Run the Analysis

1.  **Database Setup:** Create a new database instance.
2.  **Schema Creation:** Run the queries in [`sql/schema_setup.sql`](./sql/schema_setup.sql) to create the `Books`, `Customers`, and `Orders` tables.
3.  **Data Loading:** Import the three CSV files from the `data/` folder into the corresponding tables.
4.  **Analysis:** Execute the analytical queries found in [`sql/analysis_queries.sql`](./sql/analysis_queries.sql).

## 💡 Key Analysis Queries

The [`analysis_queries.sql`](./sql/analysis_queries.sql) file contains the full set of SQL commands, including:

| Objective | SQL Concept Demonstrated |
| :--- | :--- |
| **Total Revenue** and **Average Order Value (AOV)** | Aggregate Functions (`SUM`, `AVG`) |
| **Top 5 Best-Selling Books** | `JOIN`, `GROUP BY`, `ORDER BY`, `LIMIT` |
| **Customers with High Spend** | Subqueries and `HAVING` clause |
| **Customers with No Orders** | `LEFT JOIN` and `WHERE IS NULL` |
| **Monthly Sales Tracking** | Creating a `VIEW` |

## 📊 Results and Screenshots

* The results of running these queries on the database are saved in the [`output/screenshots/`](./output/screenshots) directory.
* The **Total Revenue** calculated from the `Orders` table was: [Insert your calculated number here, e.g., $156,000.50]
* The **Top Selling Book** was: [Insert book title here, e.g., 'Configurable modular throughput']

---

