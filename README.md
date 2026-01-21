🎬 Movie Ticket Booking System (Database Project)

📌 Project Overview

This project is a Relational Database–driven Movie Ticket Booking System designed to simulate a real-world online booking workflow. It focuses on database design, SQL operations, and data integrity while preventing issues like double booking or overbooking.

The system demonstrates how databases are used in practical applications such as movie ticket platforms by managing movies, theatres, shows, seats, users, and bookings efficiently.

🎯 Objectives

Design a well-structured relational database schema

Implement CRUD operations using SQL

Simulate a real-time movie ticket booking process

Maintain data integrity and consistency

Provide admin control over movies and show management

Prevent double booking / overbooking of seats

Enhance understanding of real-world database applications

🛠️ Technologies Used

Database: MySQL / PostgreSQL (any RDBMS)

Language: SQL

Tools: MySQL Workbench / pgAdmin / SQL Server Management Studio

🗂️ Database Schema Overview

Main Tables:

Users – Stores customer and admin details

Movies – Movie information (title, genre, duration, rating)

Theatres – Theatre and location details

Screens – Screens available in each theatre

Shows – Movie show timings

Seats – Seat layout and availability

Bookings – Booking transactions

Payments – Payment details (optional)

Relationships:

One movie → Many shows

One theatre → Many screens

One show → Many seats

One user → Many bookings

🔄 CRUD Operations

The project supports complete CRUD functionality:

➕ Create

Add new movies, theatres, screens, shows, and seats

Register users

Create bookings

📖 Read

View available movies and shows

Check seat availability

View booking history

✏️ Update

Update movie details

Modify show timings

Change seat status after booking

❌ Delete

Remove movies or shows (admin only)

Cancel bookings

⏱️ Real-Time Booking Simulation

Seat availability is checked before booking

Seats are locked during booking to avoid conflicts

Booking confirmation updates seat status immediately

🔐 Data Integrity & Consistency

Primary & Foreign Keys enforce relationships

Constraints prevent invalid data

Transactions ensure atomic booking operations

Unique constraints prevent duplicate seat booking

👨‍💼 Admin Features

Add / update / delete movies

Schedule and manage shows

Manage theatres and screens

Monitor bookings

🚫 Double Booking Prevention

Seat status validation before confirmation

Transaction control using COMMIT and ROLLBACK

Unique constraints on show-seat combinations

📁 Project Structure

Movie-Ticket-Booking-System/
│── schema.sql
│── insert_data.sql
│── crud_operations.sql
│── sample_queries.sql
│── README.md

▶️ How to Run the Project

Clone the repository

git clone https://github.com/manjulanarayanan0/movie-ticket-booking-system.git

Import schema.sql into your database

Run insert_data.sql to add sample data

Execute CRUD queries from crud_operations.sql

📌 Future Enhancements

User authentication

Dynamic pricing

Online payment integration

Web or mobile frontend

📚 Learning Outcomes

Strong understanding of database normalization

Hands-on experience with SQL queries and transactions

Practical exposure to real-world booking systems

🧑‍💻 Author

ManjulaNarayanan📧 Email: Manjulanarayanan0.gmailcom🔗 GitHub: https://github.com/manjulanarayanan0/

⭐ If you like this project, don’t forget to star the repository!

