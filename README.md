# 📚 Online Bookstore SQL Project

This SQL project simulates an **Online Bookstore** database. It includes schema creation, data import, and a set of basic to advanced SQL queries for data analysis.

---

## 📄 File Included

- `SQL – Project on SQL - SOLVED.sql` – Contains all SQL commands:
  - Database & table creation
  - Data import instructions
  - 20+ SQL queries (basic and advanced)

---

## 🗂️ Database Structure

The project uses the following tables:

- **Books**
  - `Book_ID`, `Title`, `Author`, `Genre`, `Published_Year`, `Price`, `Stock`
- **Customers**
  - `Customer_ID`, `Name`, `Email`, `Phone`, `City`, `Country`
- **Orders**
  - `Order_ID`, `Customer_ID`, `Book_ID`, `Order_Date`, `Quantity`, `Total_Amount`

---

## 🛠️ How to Use

1. Run the script in a **PostgreSQL** environment.
2. Import CSV data into the respective tables using the `COPY` commands (update file paths as needed).
3. Execute the SQL queries to perform analysis.

---

## ✅ SQL Query Highlights

### 🔹 Basic Queries

1. Books in the *Fiction* genre  
2. Books published after 1950  
3. Customers from Canada  
4. Orders placed in November 2023  
5. Total book stock  
6. Most expensive book  
7. Orders with quantity > 1  
8. Orders with total > $20  
9. List of available genres  
10. Book with the lowest stock  
11. Total revenue from all orders  

### 🔹 Advanced Queries

1. Total books sold by genre  
2. Average price of *Fantasy* books  
3. Customers with at least 2 orders  
4. Most frequently ordered book  
5. Top 3 expensive *Fantasy* books  
6. Total books sold by author  
7. Cities where customers spent over $30  
8. Highest spending customer  
9. Remaining stock after orders  

---

## 📊 Sample Use Cases

- Analyzing sales performance by genre or author
- Finding top customers
- Managing inventory and stock levels
- Evaluating revenue and order trends

---

## 📌 Notes

- Update CSV file paths before running the `COPY` command.
- Tested on **PostgreSQL**. May need slight changes for other SQL platforms.

---

## 👨‍💻 Author

> This project was completed as part of a SQL learning initiative. Feel free to fork, use, or improve it!
by PUNEET TIWARI

