# ☕ Cafe Management System

A web-based Cafe Management System built using **Java, Spring Boot, Thymeleaf, and MySQL** to simplify cafe operations, including menu management, order processing, and billing.

## 📌 Project Overview

The Cafe Management System aims to make daily cafe operations faster, easier, and more organized. It provides a centralized platform to manage food and beverage items, customer orders, and billing information.

## ✨ Features

- **Menu Management** – Add, view, update, and delete menu items.
- **Order Management** – Create and manage customer orders.
- **Billing System** – Calculate bills based on item prices and quantities.
- **Category Management** – Organize menu items into different categories.
- **Order Tracking** – Track order status, such as pending, preparing, and completed.
- **Database Integration** – Store and manage application data using MySQL.
- **User-Friendly Interface** – Access cafe operations through a web interface.

## 🛠️ Technologies Used

- **Programming Language:** Java 21
- **Backend Framework:** Spring Boot
- **Frontend:** HTML, CSS, Thymeleaf
- **Database:** MySQL
- **Data Access:** Spring Data JPA / Hibernate
- **Build Tool:** Maven
- **Development Environment:** Visual Studio Code

## ⚙️ Prerequisites

Before running the project, install:

- Java JDK 21
- MySQL Server and MySQL Workbench
- Maven (or use the included Maven Wrapper)
- Visual Studio Code or another Java IDE

## 🚀 Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/cafe-management.git
   ```

2. Open the project directory:

   ```bash
   cd cafe-management
   ```

3. Create the MySQL database:

   ```sql
   CREATE DATABASE cafe_management;
   ```

4. Configure `src/main/resources/application.properties`:

   ```properties
   spring.application.name=cafe-management
   spring.datasource.url=jdbc:mysql://localhost:3306/cafe_management
   spring.datasource.username=root
   spring.datasource.password=YOUR_MYSQL_PASSWORD
   spring.jpa.hibernate.ddl-auto=update
   spring.jpa.show-sql=true
   spring.jpa.properties.hibernate.format_sql=true
   ```

   Replace `YOUR_MYSQL_PASSWORD` with your local MySQL password. **Never upload your actual database password to GitHub.**

5. Run the application on Windows:

   ```powershell
   .\mvnw.cmd spring-boot:run
   ```

6. Open your browser at:

   ```text 

