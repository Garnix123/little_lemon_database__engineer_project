# 🍋 Little Lemon — End-of-Course SQL Project

## 📌 Overview
Little Lemon is a family-owned Mediterranean restaurant in Chicago.  
- This project showcases practical SQL skills for a hospitality use case: customer records, table bookings, menu pricing, and operational reporting.

**Why does this project matter? What did I solve?**
- Demonstrates **core SQL fluency** across DDL, DML, joins, grouping, subqueries, views, and stored procedures.
- Solves **real restaurant problems**: analyzing busy days, tracking guests per booking, updating menu prices, and preparing data for reports.
- Highlights **clean, production-style queries** and attention to correctness.

**Industry:** Restaurants / Hospitality / F&B

---

## 🗃️ Schema (starter tables)
- **Customers**(CustomerID, FullName, PhoneNumber)
- **Bookings**(BookingID, BookingDate, TableNumber, NumberOfGuests, CustomerID)
- **Courses**(CourseName, Cost)
- **DeliveryAddress**(ID, Address, Type, CustomerID) ← created in this project

---

## 📊 Visualizations
**Bookings by Date (counts)**  
<img width="1000" height="600" alt="Image" src="https://github.com/user-attachments/assets/72e73c29-e818-4183-a09c-0db7e0e9baf1" />

_Insight:_ 2021-11-11 was the busiest day (4 bookings). This informs staffing and inventory planning.

---

## 🔧 SQL Features & Functions Used
This project covers **all core SQL categories** with specific statements and functions:

- **DDL (Data Definition Language)**  
  - `CREATE TABLE` (DeliveryAddress, BookingsView)  
  - `ALTER TABLE` (adding `Ingredients` column)  
  - `CREATE VIEW` (BookingsView)

- **DML (Data Manipulation Language)**  
  - `INSERT INTO` (Customers, Bookings, Courses)  
  - `UPDATE` (Kabasa price adjustment)  
  - `REPLACE INTO` (demonstrating alternative update method)

- **DQL (Data Query Language)**  
  - `SELECT` (all records, filtered queries)  
  - `JOIN` (`INNER JOIN` between Customers & Bookings)  
  - `BETWEEN` (date filtering)  
  - `GROUP BY` with `COUNT()` (daily booking totals)  
  - `Subqueries` (customers who booked on a specific date)  
  - `ORDER BY` (results sorted by date)

- **Views & Stored Procedures**  
  - `CREATE VIEW` → BookingsView  
  - `CREATE PROCEDURE` → `GetBookingsData(InputDate DATE)`  

- **String & Formatting Functions**  
  - `CONCAT()` → Create user-friendly booking details string  

