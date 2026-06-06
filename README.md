Computer Shop Repair Management System
Project Description

The Computer Shop Repair Management System is a desktop application developed using Java NetBeans and MySQL. The purpose of the system is to help a computer repair shop manage customers, technicians, services, and repair transactions in an organized and efficient way.

Instead of recording repair jobs manually, the system stores information in a database where users can easily add, update, search, and delete records. The system also demonstrates the use of relational databases by connecting multiple tables using foreign keys.

This project was created to apply the concepts of Java programming, database management, CRUD operations, and SQL relationships.

System Features
1. Customer Management

This module allows users to manage customer information.

Functions:

• Add new customers
• Update customer information
• Delete customer records
• Search customer records
• Display all customers in a table

Stored Information:

• Customer ID
• Name
• Phone Number
• Address

2. Technician Management

This module stores information about technicians who perform repair services.

Functions:

• Add technicians
• Update technician information
• Delete technician records
• Search technicians
• Display all technicians in a table

Stored Information:

• Technician ID
• Name
• Specialization

3. Service Management

This module manages the services offered by the computer shop.

Functions:

• Add services
• Update service prices
• Delete services
• Search services
• Display all services in a table

Stored Information:

• Service ID
• Service Name
• Price

4. Repair Order Management

This is the main feature of the system.

The Repair Order module allows users to create repair transactions by selecting existing customers, technicians, and services from the database.

Functions:

• Create repair orders
• Assign technicians
• Select services
• Calculate service subtotal
• Track repair status
• Delete repair orders
• Display repair history

Repair Status Options:

• Pending
• Completed
• Released

How the System Works
1. The user creates customers, technicians, and services.
2. These records are stored in the MySQL database.
3. When creating a repair order, the system loads existing customers, technicians, and services into ComboBoxes.
4. The user selects the desired records and enters the quantity.
5. The system automatically calculates the subtotal based on the selected service price.
6. The repair order is saved into the database.
7. All transactions are displayed in a JTable for easy monitoring and management.

Installation Guide
Requirements

Before running the system, make sure the following software is installed:

• Java JDK 8 or higher
• Apache NetBeans IDE
• MySQL Server
• MySQL Connector/J


How to Run the System:
1. Download or clone the project from GitHub.
2. Open the project in Apache NetBeans IDE.
3. Create a MySQL database named computer_shop_system.
4. Import the provided SQL file into the database to create all required tables.
5. Open the DBConnection.java file and make sure the database URL, username, and password match your MySQL configuration.
6. Add the MySQL Connector/J library to the project's Libraries folder in NetBeans.
7. Clean and Build the project by clicking Run > Clean and Build Project.
8. Run the Dashboard.java file.
9. Use the Dashboard to access the Customer Management, Technician Management, Service Management, and Repair Order Management modules.
10. Add customers, technicians, and services before creating repair orders, since the Repair Order module loads these records from the database.
11. Create repair orders by selecting a customer, technician, service, quantity, and repair status, then click Save Order.
12. The system will automatically store and display all records in the MySQL database.
