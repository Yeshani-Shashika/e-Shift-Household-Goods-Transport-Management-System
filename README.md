# e-Shift Household Goods Transport Management System

## Overview

e-Shift is a desktop-based transport management system developed using **C# Windows Forms** and **SQL Server**. The system automates household goods transport operations by managing customers, transport jobs, loads, vehicles, drivers, assistants, and reports through a secure role-based platform.

## Features

* Customer registration and login
* Admin and customer role-based access
* Transport job management
* Load and product management
* Vehicle and transport unit allocation
* Job approval and status tracking
* Customer and admin dashboards
* Report generation
* SQL Server database integration
* Input validation and exception handling

## Technologies Used

* C#
* Windows Forms (WinForms)
* .NET Framework
* SQL Server
* ADO.NET
* Visual Studio 2022

## System Requirements

* Windows 10 or later
* .NET Framework 4.7.2
* SQL Server 2022
* Visual Studio 2022
* Minimum 8GB RAM

## Installation

1. Clone this repository:

```bash
git clone https://github.com/your-username/e-shift-management-system.git
```

2. Open the project in Visual Studio.

3. Create a database named:

```sql
EShiftDB
```

4. Run the provided SQL script to create tables.

5. Update the connection string in `appsettings.json`:

```json
{
  "ConnectionStrings": {
    "DefaultConnection": "Data Source=YOUR_SERVER;Initial Catalog=EShiftDB;Integrated Security=True;TrustServerCertificate=True"
  }
}
```

6. Restore NuGet packages:

```bash
NuGet restore E-Shift.sln
```

7. Build and run the project.

## Default Admin Login

```text
Username: admin
Password: admin123
```

## Project Architecture

The system follows a layered architecture:

* Presentation Layer (WinForms UI)
* Business Logic Layer
* Data Access Layer (ADO.NET)
* Database Layer (SQL Server)

## OOP Concepts Used

* Encapsulation
* Inheritance
* Polymorphism
* Abstraction

## Main Modules

### Customer Module

* Register/Login
* Create transport jobs
* View job history
* Track job status

### Admin Module

* Manage customers
* Approve or reject jobs
* Assign transport units
* Generate reports
* Manage products and staff

## Future Improvements

* Cloud integration
* Mobile application support
* Online payment gateway
* Real-time GPS tracking

## Author

**B.G. Yeshani Shashika Jayawardana**
BEng (Hons) in Software Engineering
London Metropolitan University

## License

This project is developed for educational purposes only.
