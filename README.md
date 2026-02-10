# RTO-Management-System
Web-based RTO Management System using PHP and MySQL
# 🚦 RTO Management System (RTOMS)

A web-based RTO Management System developed using **PHP** and **MySQL** that automates the process of applying for Learning and Driving Licences.


## 📌 Project Overview
The RTO Management System (RTOMS) helps digitize RTO operations by allowing users to apply for licences online, RTO officers to verify and process applications, and administrators to manage and monitor the overall system.


## 👥 User Roles
- **User (Citizen)** – Apply for Learning/Driving Licence and track application status
- **RTO Officer** – Verify, approve, or reject licence applications
- **Admin** – Manage RTO offices, users, states, cities, and monitor system activity


## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** PHP
- **Database:** MySQL
- **Server:** Apache (XAMPP)


## ✨ Features
- User registration and login
- Learning Licence application
- Driving Licence application
- Application status tracking
- RTO approval and rejection workflow
- Admin dashboard for system management


## ⚙️ Installation & Setup

### Requirements
- XAMPP (Apache & MySQL)
- Web Browser (Chrome recommended)

### Steps to Run the Project
## Note
Download the `rtoms.zip` file and extract it before running the project.

1. Download the repository
2. Extract `rtoms.zip`
3. Copy the extracted `rtoms` folder to:
   ```
   C:\xampp\htdocs\
   ```
4. Open phpMyAdmin in browser:
   ```
   http://localhost/phpmyadmin
   ```
5. Create a database named:
   ```
   rtomsdb
   ```
6. Import the `rtomsdb.sql` file into the database
7. Start **Apache** and **MySQL** from XAMPP Control Panel
8. Run the project in browser:
   ```
   http://localhost/rtoms
   ```

## 🔐 Sample Login Credentials

### Admin
- Username: `admin`
- Password: `Test@123`

### RTO Officer
- Username: `rtobuland`
- Password: `Test@123`

### User
- Email: `garima12@gmail.com`
- Password: `Test@123`


## 🔄 Project Workflow
```
User applies for licence
        ↓
RTO verifies application
        ↓
Application approved / rejected
        ↓
User checks updated status
        ↓
Admin monitors entire system
```
## 📂 Repository Contents
- `rtoms.zip` – Project source code  
- `rtomsdb.sql` – Database file  
- `README.md` – Project documentation
  

## 🎓 Learning Outcome
This project helped me understand:
- Role-based access control
- PHP–MySQL integration
- Database-driven web applications
- Real-world workflow implementation


## 👩‍💻 Author
**Ushasri Dasari**
