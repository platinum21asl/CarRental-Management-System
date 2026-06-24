# Car Rental Management System

A web-based Car Rental Management System built with CodeIgniter 3 (CI3) to manage vehicle rentals, customer data, booking transactions, and rental operations efficiently.

## Overview

This project was developed to simplify car rental business processes by providing an integrated system for managing vehicles, customers, and rental transactions through a centralized web application.

The application is built using the MVC architecture provided by CodeIgniter 3, ensuring maintainability, scalability, and clean code organization.

---

## Features

* Vehicle Management

  * Add, edit, update, and delete vehicle data
  * Manage vehicle availability status

* Customer Management

  * Register and manage customer information
  * View customer rental history

* Rental Transactions

  * Create rental orders
  * Manage vehicle borrowing and returning
  * Calculate rental costs

* Administrative Dashboard

  * Monitor rental activities
  * Manage operational data

* Database Integration

  * MySQL database support
  * Structured relational data management

---

## Technology Stack

### Backend

* PHP
* CodeIgniter 3

### Frontend

* HTML5
* CSS3
* JavaScript

### Database

* MySQL

### Development Tools

* Composer
* Apache / XAMPP

---

## Project Structure

```bash
CarRental-Management-System/
│
├── application/
├── assets/
├── system/
├── user_guide/
│
├── rental_mobil.sql
├── composer.json
├── index.php
└── .htaccess
```

## Installation

### 1. Clone Repository

```bash
git clone https://github.com/platinum21asl/CarRental-Management-System.git
```

### 2. Move to Project Directory

```bash
cd CarRental-Management-System
```

### 3. Create Database

Create a new MySQL database:

```sql
CREATE DATABASE rental_mobil;
```

### 4. Import Database

Import the provided SQL file:

```bash
rental_mobil.sql
```

### 5. Configure Database

Open:

```bash
application/config/database.php
```

Update database credentials:

```php
$db['default'] = array(
    'hostname' => 'localhost',
    'username' => 'root',
    'password' => '',
    'database' => 'rental_mobil',
    'dbdriver' => 'mysqli'
);
```

### 6. Configure Base URL

Open:

```bash
application/config/config.php
```

Update:

```php
$config['base_url'] = 'http://localhost/CarRental-Management-System/';
```

### 7. Run Application

Start Apache and MySQL through XAMPP or Laragon, then access:

```bash
http://localhost/CarRental-Management-System
```

---

## Screenshots

Add screenshots of:

* Dashboard
* Vehicle Management
* Customer Management
* Rental Transaction
* Reports

Example:

```markdown
![Dashboard](docs/dashboard.png)
```

---

## Future Improvements

* Online booking system
* Payment gateway integration
* Vehicle maintenance tracking
* Email notifications
* Reporting and analytics dashboard
* REST API integration
* Multi-user role management

---

## License

This project is licensed under the MIT License.

---

## Author

Developed by Daniel Renato.

GitHub:
https://github.com/platinum21asl
