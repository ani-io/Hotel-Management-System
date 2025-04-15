# 🏨 Hotel Reservation System (Java + MySQL)

A simple console-based Hotel Management System built in Java using JDBC and MySQL. It allows hotel staff to manage room reservations through a menu-driven interface.

## 🚀 Features

- 📥 **Reserve a Room**
- 📋 **View All Reservations**
- 🔍 **Get Room Number by Reservation ID**
- ✏️ **Update Reservation Details**
- ❌ **Delete Reservation**
- 🧾 **Exit System with Countdown**

## 🛠 Tech Stack

- **Java (JDBC)**
- **MySQL** for data storage
- **SQL** for reservation table and queries

## 🗃 Database Schema

Make sure your MySQL database `hotel_db` has a table like this:

```sql
CREATE TABLE reservations (
    reservation_id INT AUTO_INCREMENT PRIMARY KEY,
    guest_name VARCHAR(100),
    room_number INT,
    contact_number VARCHAR(20),
    reservation_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
