# 🧑‍💼 Recruitment Management System
---
## 📌 Project Overview

The Recruitment Management System (RMS) is a web-based application designed to streamline and manage the end-to-end recruitment process for institutions, companies, and placement cells.

The system supports multiple user roles such as:

- Applicants (students/job seekers)

- Employers

- Administrators

It enables online job postings, application management, resume handling, interview scheduling, shortlisting, and reporting — all through a centralized platform.

This project is built using PHP, MySQL, HTML, CSS, and JavaScript and follows a modular structure for easy maintenance and scalability.

## 🎯 Objectives

Automate the recruitment and placement process

Reduce manual paperwork and administrative overhead

Provide a centralized system for job postings and applications

Enable efficient resume shortlisting and interview tracking

Support employer–applicant interaction through a web interface

## 🏗️ Project Architecture

The system follows a multi-module PHP-based architecture with server-side scripting and database-backed storage.

High-Level Components:

Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

Reports & Exports: PDF, CSV

Authentication & Authorization

## 📂 Project Structure
recruit_management_system/
│
├── applications/        # Job applications handling
├── resume/              # Resume upload & management
├── coverletters/        # Cover letter handling
├── interview/           # Interview scheduling & records
├── shortlist/           # Shortlisted candidates
├── placement/           # Placement records
├── reports/             # Recruitment & placement reports
├── export_file/         # Data export functionality
├── SQL/                 # Database scripts (.sql files)
├── PDF/                 # Generated PDF reports
├── documentation/       # System documentation
│
├── student_info/        # Applicant (student) data
├── new_employer/        # Employer registration & management
├── preferences/         # User & system preferences
├── search/              # Job and candidate search modules
├── history/             # Recruitment history logs
├── plugins/             # Third-party plugins
│
├── header.inc           # Header layout
├── footer.inc           # Footer layout
├── index.php            # Main entry point
├── welcome.inc          # Welcome page
├── welcome_applicant.inc
├── welcome_employer.inc
│
├── LICENSE.txt
├── README.txt
└── VERSION

## 👥 User Roles & Functionalities
### 👨‍🎓 Applicant (Student)

Register & login

Upload resumes and cover letters

Apply for jobs

Track application status

View interview schedules

##🏢 Employer

Register & login

Post job openings

View applicant resumes

Shortlist candidates

Schedule interviews

Generate reports

##🛠️ Administrator

Manage users (students & employers)

Monitor recruitment activities

Generate system reports

Maintain system configurations

##🧠 Key Features

User authentication & role-based access

Resume & document management

Job posting & application tracking

Candidate shortlisting

Interview scheduling

Search & filtering system

PDF & data export functionality

Modular and extensible design

##🛠️ Technologies Used
Layer	Technology
Frontend	HTML, CSS, JavaScript
Backend	PHP
Database	MySQL
Server	Apache (XAMPP / WAMP / LAMP)
Reports	PDF generation
Scripting	PHP Modules
⚙️ Installation & Setup
1️⃣ Prerequisites

PHP 7.x or higher

MySQL

Apache Server

XAMPP / WAMP / LAMP recommended

2️⃣ Database Setup

Open phpMyAdmin

Create a new database (e.g., recruitment_db)

Import SQL files from:

/SQL/

3️⃣ Project Setup

Copy the project folder to:

htdocs/ (XAMPP)


Update database credentials in configuration files (if any)

4️⃣ Run the Application

Open browser and navigate to:

http://localhost/recruit_management_system/

🔐 Security Considerations

Password hashing recommended (if not already implemented)

Input validation required to prevent SQL Injection

Role-based access control should be enforced

Secure file uploads (resume & documents)

📈 Future Enhancements

Email notifications for job updates

Resume ranking using AI/ML

Online interview integration

Admin analytics dashboard

REST API support

Modern UI using React or Bootstrap

Cloud deployment

📜 License

This project is licensed under the terms mentioned in LICENSE.txt.

##👨‍💻 Author

Ashwani Pandey
Software & Web Application Developer

📞 Support

For issues, feature requests, or improvements:

Create an issue in the repository

Contact the project maintainer
