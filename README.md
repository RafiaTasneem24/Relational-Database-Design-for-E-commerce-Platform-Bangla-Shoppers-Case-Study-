# Relational-Database-Design-for-E-commerce-Platform-Bangla-Shoppers-Case-Study-
Designed and implemented a relational database for an e-commerce platform using ERD modeling and SQL, including complex queries, joins, constraints, and views to ensure data integrity and efficient data retrieval.

# 🛒 Relational Database Design for E-commerce Platform (Bangla Shoppers)

## 📌 Overview
This project presents the design and implementation of a relational database system for **Bangla Shoppers**, an e-commerce platform specializing in beauty, skincare, and lifestyle products.  

The project focuses on structuring and managing data efficiently using **Entity Relationship Diagrams (ERD)** and **SQL**, enabling scalable and reliable data operations.

---

## 🎯 Objectives
- Design a structured relational database for an e-commerce system  
- Model real-world relationships between entities (customers, products, orders, etc.)  
- Implement SQL queries for data retrieval and analysis  
- Ensure data integrity using constraints and relational rules  

---

## 🧱 Database Design

### 🔹 Entity Relationship Diagram (ERD)
- Designed ERD to represent relationships between:
  - Customers  
  - Orders  
  - Products  
  - Brands  
  - Sellers  
- Includes:
  - One-to-Many relationships  
  - Many-to-Many relationships (via junction tables like `OrderProduct`)  

---

## 🛠️ Technologies Used
- **SQL**
- **Relational Database Design**
- **ERD Modeling**

---

## 🧮 Key Features

### 🔹 SQL Queries Implemented
- Basic SELECT queries  
- **Joins** (NATURAL JOIN, INNER JOIN)  
- **Subqueries**  
- **Aggregation & Group By with HAVING**  
- **Cross Join / Self Join**  

### 🔹 Data Integrity Constraints
- `CHECK` constraints (e.g., valid ratings, gender values)  
- `NOT NULL` constraints  
- `FOREIGN KEY` constraints  

### 🔹 Referential Integrity
- `ON DELETE RESTRICT`  
- `ON DELETE CASCADE`  
- `ON UPDATE CASCADE`  

---

## 👁️ Views
- Created SQL views to simplify complex queries  
- Example: `ProductBrandView` combining product and brand data  

---

## 📊 Business Value
- Efficient data organization for an e-commerce platform  
- Supports:
  - Product management  
  - Customer tracking  
  - Order processing  
- Enables meaningful insights through structured queries  

---

## ⚠️ Note
This is a **simulated database project** created using publicly available data. Sensitive business data such as customer transactions was not accessible and has been modeled for academic purposes.

---

## 🚀 Future Improvements
- Integrate with a frontend application  
- Add real-time data handling  
- Implement advanced analytics/dashboard  
- Optimize queries for performance  

---

## 👩‍💻 Author
**Rafia Tasneem**  
Master’s Graduate – Data Science  

---
