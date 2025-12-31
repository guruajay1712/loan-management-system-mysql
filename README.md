# Loan Management System (MySQL)

## 📌 Project Overview
This project is a Loan Management System developed using MySQL to manage
customers, loan details, repayments, and loan status efficiently.
It is designed to simulate real-world banking and financial operations
with proper database structure and business logic.

## 🎯 Objective
- Maintain structured records of customers and loans
- Track loan repayments and remaining balances
- Identify active, closed, and overdue loans
- Demonstrate strong SQL and database design skills

## 🛠️ Technologies Used
- MySQL
- SQL (Joins, Subqueries, Triggers)
- ER Diagram

## 📂 Database Tables
- customers
- loan_types
- loans
- repayments
- loan_status

## ⚙️ Key Features
- Customer and loan management
- Repayment and balance tracking
- Automatic loan status updates using triggers
- Identification of overdue loans
- Analytical and reporting queries

## 📊 Sample Queries Implemented
- List of active loans
- Total loan amount per customer
- Overdue customers report
- Monthly repayment summary

## 📥 Data Loading
CSV files were loaded into MySQL tables using the `LOAD DATA LOCAL INFILE` command for efficient bulk data insertion.

## 🔄 Business Logic Implemented
- Trigger to update loan balance after repayment
- Automatic status change to CLOSED when loan balance becomes zero

## ▶️ How to Run the Project
1. Create the database `loan_management_db`
2. Run table creation scripts
3. Insert sample data
4. Execute triggers
5. Run analytical queries

## 💡 Skills Demonstrated
- Database design and normalization
- Foreign key relationships
- Business logic using SQL
- Data analysis mindset
