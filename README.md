Features
1. User Authentication
Secure login for customers and admins.
Role-based access control with encrypted password storage.
2. Vehicle Management
CRUD operations for managing vehicle information (make, model, availability, pricing).
Dynamic vehicle availability based on real-time reservations.
3. Reservation System
Create, update, and cancel vehicle reservations.
Conflict resolution to handle overlapping bookings.
Email/SMS notifications for booking confirmations and reminders.
SQL Database
The platform is backed by a SQL database with the following schema:

Customer Table: Stores customer details and login credentials.
Vehicle Table: Holds vehicle information such as make, model, availability, and daily rates.
Reservation Table: Tracks reservations, their status, and associated costs.
Admin Table: Stores admin details for system management.
Database Connectivity
JDBC Connectivity: The application uses JDBC to connect to the SQL database, execute queries, and handle results.
DBConnUtil Class: A utility class that manages the database connection and ensures efficient resource handling.
