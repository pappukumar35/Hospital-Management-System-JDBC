# Hospital Management System

A comprehensive Hospital Management System developed using Core Java and JDBC. This project is designed to help manage patient information, doctor details, and appointment scheduling in a hospital setting.

## Features

- Adding Patient Records
- Adding Doctor Information
- Viewing Patient Details
- Viewing Doctor Details
- Booking Appointments
- Checking Doctor Availability

## Technologies Used

- Core Java
- JDBC (Java Database Connectivity)
- MySQL Database

## Database Schema

The project uses the following database tables:

1. `patient`
2. `doctor`
3. `appointment`

(Detailed schema information to be added)

## Setup Instructions

1. **Java Development Kit (JDK)**: Ensure you have JDK 8 or higher installed.

2. **MySQL Database**: Install MySQL Server and MySQL Workbench.

3. **JDBC Driver**: Download the MySQL JDBC driver and add it to your project's classpath.

4. **Database Setup**:
   - Create a new database named `hospital_management`
   - Run the SQL scripts provided in the `database` folder to create the necessary tables

5. **Configure Database Connection**:
   - Open `src/main/java/config/DatabaseConfig.java`
   - Update the database URL, username, and password according to your MySQL setup

6. **Compile the Project**:
