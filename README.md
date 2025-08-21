# 🍋 Little Lemon — End-of-Course SQL Project

## 📌 Overview
Little Lemon is a family-owned Mediterranean restaurant in Chicago.  
- This project showcases practical SQL skills for a hospitality use case: customer records, table bookings, menu pricing, and operational reporting.

**Why it matters (for HR & hiring managers):**
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
<img width="1250" height="680" alt="Image" src="https://github.com/user-attachments/assets/72e73c29-e818-4183-a09c-0db7e0e9baf1" />

_Insight:_ 2021-11-11 was the busiest day (4 bookings). This informs staffing and inventory planning.

---
