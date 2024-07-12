
---

# Event Management System

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
The Event Management System is a web application designed to help users organize and manage events efficiently. This system allows users to create, update, delete, and view events, as well as manage participants and event details.

## Features
- User Registration and Login
- Event Creation and Management
- Participant Registration
- Event Scheduling
- Email Notifications
- Admin Dashboard
- Responsive Design

## Technologies Used
- **Frontend:**
  - HTML
  - CSS
  - JavaScript
- **Backend:**
  - PHP
  - SQL
- **Database:**
  - phpMyAdmin

## Installation
To set up the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/KaizenBuild/College_Project.git
   ```

2. **Set up the database:**
   - Open phpMyAdmin.
   - Create a new database named `event_management`.
   - Import the provided SQL file (`database.sql`) to set up the tables.
   
3. **Configure the database connection:**
   - Open the `config.php` file.
   - Update the database credentials (host, username, password, database name) as per your local setup.
   
   ```php
   <?php
   $servername = "localhost";
   $username = "root";
   $password = "";
   $dbname = "event_management";

   // Create connection
   $conn = new mysqli($servername, $username, $password, $dbname);

   // Check connection
   if ($conn->connect_error) {
     die("Connection failed: " . $conn->connect_error);
   }
   ?>
   ```

4. **Run the application:**
   - Place the project files in your web server's root directory (e.g., `htdocs` for XAMPP, `www` for WAMP).
   - Start your local server (e.g., Apache) and navigate to `http://localhost/event-management-system` in your web browser.

## Usage
1. **Register a new user or login as an existing user.**
2. **Navigate to the dashboard to create and manage events.**
3. **Register participants for events and manage their details.**
4. **View the schedule and details of upcoming events.**

## Contact
For any questions or inquiries, please contact:
- Your Name: [jyotirmay231@gmail.com](mailto:jyotirmay231@gmail.com)
- GitHub: [https://github.com/KaizenBuild](https://github.com/KaizenBuild/College_Project)

---
