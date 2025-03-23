# Dealership Management System

## Description
This project is a resource and service management system designed for a network of dealerships. The system manages vehicles, their owners, and the sales process, as well as calculating salespeople's salaries with commissions. The system supports full CRUD operations on tables in a SQL Server database and includes additional features like listing vehicles by mileage and system version, and calculating salaries with monthly sales commissions.

## Features
1. **Vehicle Management**:
   - Each vehicle has the following attributes:
     - **Chassis Number**
     - **Model**
     - **Year**
     - **Color**
     - **Value**
     - **Mileage**
     - **Accessories**
     - **System Version**
     - **Owner Data**:
       - Name
       - CPF/CNPJ
       - Address
       - Email
       - Phone
       - Other personal information

2. **Sales Control**:
   - The system manages vehicle sales by **salespeople**, who receive a **1% commission** on each sale.

3. **Full CRUD**:
   - The system supports **Create, Read, Update, and Delete (CRUD)** operations on all database tables, including vehicles, owners, and salespeople.

4. **Vehicle Listing**:
   - Vehicles can be listed by:
     - **Mileage**
     - **System Version**

5. **Salary Calculation**:
   - The system calculates each salesperson's salary, based on:
     - **Current minimum wage**
     - **Monthly sales commissions** (1% of sales)

6. **Exception Handling**:
   - The system includes error handling, with **logs stored** in a file for persistence of errors and exceptions.

7. **Creative Feature**:
   - [Add details of the creative or innovative feature included in the system.]

## Requirements
- **Technologies Used**:
  - **.NET Core** with **Entity Framework** for REST API implementation.
  - **SQL Server** as the relational database.
  - **Serilog** for logging and exception handling.
