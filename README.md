# ✈️ Airline Management System

A desktop-based Airline Management System built using **Java Swing** and **MySQL**, allowing airline staff to manage customer bookings, cancellations, and boarding efficiently.

## 🚀 Features

- ✅ Login Authentication (Admin)
- 🧾 Add Customer Details
- 🛫 Flight Booking (with real-time passenger fetch using Aadhar)
- 📋 View Flight and Journey Details
- 🎫 Generate Boarding Pass
- ❌ Cancel Booked Tickets

## 🛠️ Technologies Used

- **Java Swing** – For GUI components
- **JDBC (Java Database Connectivity)** – For interacting with MySQL
- **MySQL** – Backend relational database
- **NetBeans IDE** – Development environment
- **JDateChooser** – For calendar-based date input
- **DbUtils** – For populating tables from ResultSet

## 📐 Methodologies and Concepts

- **Object-Oriented Programming (OOP)** – Inheritance, Encapsulation, and Modularity
- **Event-Driven Programming** – ActionListeners for handling UI events
- **Database Operations** – CRUD (Create, Read, Update, Delete) using SQL queries
- **MVC (Model-View-Controller)** – Light implementation separating UI and DB logic
- **Randomized ID Generation** – For unique PNR and ticket numbers

## 📸 UI Preview

> Includes modules like:
> - Add Customer Form
> - Book Flight Panel
> - Boarding Pass Generator
> - Cancellation Dashboard
> - Admin Home Menu

## 🧪 How to Run

1. Clone the repo  
   `git clone https://github.com/pratham13103/airlinemanagementsystem.git`

2. Import into NetBeans or any Java IDE.

3. Ensure **MySQL** is running and the database `airlinemanagementsystem` is created with proper tables.

4. Update DB credentials in `Conn.java` file.

5. Run `Login.java` to start the application.

## 🔐 Default Login

You can insert a default login manually in MySQL:

INSERT INTO login VALUES('admin', 'admin');

![App Screenshot](https://github.com/pratham13103/airlinemanagementsystem/blob/master/src/airlinemanagementsystem/icons/landing_page.png)
