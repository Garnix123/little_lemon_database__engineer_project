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

📌 **Description & Insights:**  
This bar chart shows how many bookings were made on each date between **November 10–14, 2021**.  
- **November 11th** was the busiest day, with the highest number of bookings.  
- This insight is important for **staff scheduling, kitchen preparation, and inventory management**, since it highlights peak demand days.  
- Over time, such analysis can be used to **predict seasonal patterns** and improve **customer experience** by avoiding overcrowding.  

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

---

## 🏁 Conclusion
This project demonstrates how SQL supports **day-to-day restaurant operations**: managing reservations, customers, menus, and analytics.  

It also reflects my ability to use SQL across its core domains (**definition, manipulation, queries, and programmability**).  
These skills translate beyond restaurants, applying to **finance, retail, logistics, and any data-driven industry**.

---

## 📬 Contact
💬 If you have any questions about this project, feel free to connect with me:  
- LinkedIn: [Dominik Vyleta](https://www.linkedin.com/in/dominik-vyleta-mba-a566511b2/)  
- Email: [vyleta.dom@gmail.com](mailto:vyleta.dom@gmail.com)  
