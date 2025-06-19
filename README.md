# Campus Map Web System
An interactive campus navigation web system that supports user login, building info pages, and a dynamic map interface using HTML, CSS, JS, PHP, and MySQL.

# Features
User Login & Registration
Interactive SVG-based Campus Map
Building Detail Pages (e.g. GHK, Stadium)
Backend validation using PHP + MySQL
Sidebar & Map Legends for ease of use

# structure
Fronted: CSS, Javascript, HTML
Backend: PHP
Database: MySQL

# How to RUN:
1. git clone [ https://github.com/yourname/campus-map-web.git](https://github.com/chenchun-undergraduate/Campus_map_web)
2. Create a database and table in MySQL:
   CREATE DATABASE CampusStudent;
      CREATE TABLE users (
       id INT AUTO_INCREMENT PRIMARY KEY,
       username VARCHAR(50) UNIQUE NOT NULL,
       password VARCHAR(255) NOT NULL,
       email VARCHAR(100) UNIQUE NOT NULL
      );
3. Run with local PHP server or XAMPP:
   Put project folder in htdocs/
   Access http://localhost/Campusmap/index.html

# Author

Chun Chen (Dave)  
Course: CPS3500 – Programming WWW Server  
Instructor: Dr. Hemn Barzan Abdalla  
Spring 2025
