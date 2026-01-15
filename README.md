# 🏥 Healthcare Appointment System

A web-based **Healthcare Appointment System** designed to simplify and manage appointments between patients, doctors, and hospitals. The system ensures secure authentication, efficient appointment handling, hospital management, and a basic payment workflow.

---

## 📌 Project Overview

In modern healthcare, efficient appointment management is essential. This project provides a digital platform that reduces administrative effort while improving patient–doctor interaction.

The system is built using **PHP, MySQL, HTML, CSS, and JavaScript**, focusing on usability, security, and clarity.

---

## 🚀 Features

### 👤 User Management
- Patient signup & login
- Doctor signup & login
- Admin login
- Update and delete user information
- Password hashing for security

### 🏥 Hospital & Doctor Management
- Add hospitals
- Assign doctors to hospitals
- View available hospitals
- Search doctors

### 📅 Appointment Management
- Book doctor appointments
- Book test appointments
- View appointment history
- Cancel appointments

### 💳 Payment
- Basic payment workflow
- Placeholder for future payment gateway integration

### 🔍 Search & Navigation
- Doctor and hospital search
- Organized dashboards for patients and doctors

---

## 🛠️ Tech Stack

- PHP
- MySQL
- HTML
- CSS
- JavaScript

---

## 🗂️ Project Structure

Healthcare/
│
├── admin_appointments.php
├── adminpage.php
├── change_hospitals.php
├── change_tests.php
├── check_doctor_appointments.php
├── check_patient_appointments.php
├── credits.php
├── doctor_details.php
├── sign_up.php
│
├── assets/
│   ├── 26363.png
│   ├── 5230819.jpg
│   ├── artboard_1_9X7_icon.ico
│   ├── hospimg.jpg
│   └── v870-tang-36.jpg
│
├── forms/
│   ├── add_doctor.php
│   ├── add_hospital.php
│   ├── add_test.php
│   └── appointment_form.php
│
├── includes/
│   ├── config.php
│   ├── db_connect.php
│   └── session.php
│
├── scripts/
│   ├── admin.js
│   ├── appointment.js
│   └── update_contact.js
│
├── styles/
│   ├── admin_table.css
│   ├── credits.css
│   ├── details.css
│   ├── docdet.css
│   ├── doctor_search.css
│   ├── forms.css
│   ├── home.css
│   ├── hospital_list.css
│   ├── login.css
│   ├── main_style.css
│   ├── payment.css
│   ├── select.css
│   └── table.css
│
└── README.md


---

## 📊 Database Design

- ER/EER Diagram
- Schema Diagram
- Tables: Patients, Doctors, Hospitals, Appointments, Payments

---

## 👨‍💻 Contributors

- Avishek Paul 
- Mantaqa Abedin 
- Mitul Roy Tanny 
- Nabil Hossain Chowdhury 


---

## ⚙️ Setup Instructions

1. Clone the repository  
   git clone https://github.com/your-username/healthcare-appointment-system.git

2. Move the project to your local server directory (e.g., htdocs for XAMPP)

3. Create a MySQL database and import the SQL file

4. Update database credentials in connect.php

5. Start Apache and MySQL

6. Open in browser  
   http://localhost/Healthcare-main/

---

## 🔐 Security

- Password hashing
- Role-based access
- Secure deletion of records

---

## 📌 Future Enhancements

- Payment gateway integration
- Email/SMS notifications
- Improved UI/UX
- Advanced admin dashboard

---

## 📄 License

Academic project for **CSE370 – Database Systems**
