# 🚗 Car Rental Management System  
A complete web-based Car Rental Management System built using **PHP**, **MySQL**, **HTML**, **CSS**, and **JavaScript**.  
This system allows users to browse, book, and manage car rentals while providing an admin interface to manage vehicles, bookings, testimonials, and users.

---

## 📸 Screenshots

### 🏠 Home Page
![Home Page](screenshots/Screenshot 2025-11-25 204241.png)

### 🚘 Car Listings
![Car Listings](screenshots/Screenshot 2025-11-25 204719.png)

### 📄 Car Details & Booking
![Car Details](screenshots/Screenshot 2025-11-25 204750.png)

### 📑 User Booking Details
![Booking Page](screenshots/Screenshot 2025-11-25 205036.png)

### 📝 Sign Up Page
![Sign Up](screenshots/Screenshot 2025-11-25 210028.png)

---

## 🚀 Features

### 👤 User Features
- User registration and login  
- View available cars  
- Car details with images  
- Online booking system  
- Manage bookings  
- Update profile and change password  
- Post and view testimonials  

### 🛠️ Admin Features
- Login & logout  
- Add, update, delete cars  
- Manage car brands  
- Manage bookings  
- Manage customers  
- View testimonials  
- Dashboard & statistics  

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript, Bootstrap  
- **Backend:** PHP  
- **Database:** MySQL  
- **Server:** Apache (XAMPP)

---

## 📂 Folder Structure
project/
│── admin/
│── assets/
│── includes/
│── index.php
│── car-listing.php
│── search.php
│── profile.php
│── my-booking.php
│── contact-us.php
│── ...
└── database.sql


---

## 🧰 Installation Guide (Localhost)

### 1️⃣ Install XAMPP  
Download & install: https://www.apachefriends.org/

### 2️⃣ Move project to XAMPP
Place your project inside:


### 3️⃣ Import the Database
1. Open **phpMyAdmin**
2. Create a new database (example):


3. Import `database.sql` from your project

### 4️⃣ Start Apache & MySQL

### 5️⃣ Run the Project  
Open browser:


---

## 🌐 Deployment Guide (Free Hosting)

### 🚀 Option 1: Deploy on **000WebHost** (FREE)

1. Go to https://www.000webhost.com/  
2. Create account → Create new site  
3. Upload all your files to `/public_html/`  
4. Create a new database  
5. Import `database.sql`  
6. Update `includes/config.php` with new DB credentials:

```php
$host = "localhost";
$user = "your_db_user";
$pass = "your_db_password";
$db   = "your_db_name";


