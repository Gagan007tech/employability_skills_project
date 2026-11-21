# Vehicle Service Center Management System

## Main modules
1. Job card creation and viewing
2. Service status tracking
3. Spare parts entry and billing
4. Service history by vehicle number

## Packages
- `app`: Main menu and program execution
- `model`: Customer, Vehicle, JobCard, SparePart and Admin classes
- `service`: Job card, service status, billing and history operations
- `exceptions`: Custom exception classes
- `util`: Input helper methods

## 1. Project Overview

The **Vehicle Service Center Management System** is a command-line-based application developed using Core Java. It is designed to simplify and organize the daily operations of a vehicle service center.

The system manages customer details, vehicle information, job card creation, service status tracking, spare parts billing, and service history. It provides a simple menu-driven interface that allows users to perform different service-related operations efficiently.

## 2. Key Features

- **Job Card Management:** Creates job cards with unique IDs and stores customer, vehicle, and complaint details.
- **Service Status:** Tracks vehicle servicing progress through Pending, In Progress, and Completed statuses.
- **Spare Parts Management:** Adds spare parts, quantities, and prices required for vehicle repairs.
- **Billing Management:** Calculates spare parts costs, adds labour charges, and generates the final service bill.
- **Service History:** Retrieves previous service records using the vehicle registration number.

## 3. Technologies Used

- Programming Language: Java
- Concepts: Core Java and OOP
- Collections: ArrayList
- Exception Handling: Custom Exceptions
- IDE: VS Code / NetBeans
- Interface: Command Line Interface (CLI)

## 4. Project Structure

The project is organized into the following packages:

- **app:** Contains the Main class and menu-driven program.
- **model:** Contains Admin, Customer, Vehicle, JobCard, and SparePart classes.
- **service:** Handles job cards, service status, billing, and service history.
- **exceptions:** Contains custom exception classes for error handling.
- **util:** Provides reusable input-handling methods.

## 5. OOP Concepts Implemented

- Classes and Objects
- Encapsulation
- Constructors
- Inheritance
- Polymorphism
- Abstraction
- Exception Handling
- Collection Framework

## 6. Advantages

- Reduces manual record maintenance.
- Simplifies job card creation and management.
- Provides easy service status tracking.
- Generates service bills automatically based on entered charges.
- Maintains organized vehicle service records.
- Uses modular Java packages for better code organization.

## 8. Conclusion

The Vehicle Service Center Management System provides a simple and organized solution for handling vehicle servicing activities.It combines job card management, service tracking, spare parts billing, and service history into a single Java application.

This project demonstrates the practical implementation of Core Java, Object-Oriented Programming, collections, and exception handling to solve a real-world management problem.

The program uses ArrayList for temporary in-memory storage. Records are cleared when the program exits.
