
# 🎓 Learners’ Hot-desk – A Student Friendly Job Portal

**Team Name:** The FrontEnders  
**Course:** CSE479 (Web Programming) | Section 2  
**Institution:** East West University  

![Project Status](https://img.shields.io/badge/Status-Completed-success)
![Tech Stack](https://img.shields.io/badge/PHP-MySQL-blue)
![Frontend](https://img.shields.io/badge/HTML-CSS-orange)

## 📖 Introduction

**Learners’ Hot-desk** is a centralized, web-based recruitment platform designed to bridge the gap between students (job seekers) and employers. Unlike massive commercial platforms, this system is optimized for academic and small-organization use, providing a "Hot-desk" environment where learners can easily find opportunities.

The system digitizes the recruitment lifecycle—from job posting to application management—ensuring efficiency, transparency, and data integrity. It features a responsive interface built with HTML/CSS/JS and a robust backend powered by PHP and MySQL.

---

## ✨ Features

### 👨‍🎓 For Job Seekers (Students)
*   **User Registration & Login:** Secure account creation with CV/Resume upload capabilities.
*   **Job Search:** Browse available listings and search by keywords, location, or category.
*   **Apply for Jobs:** One-click application submission using the stored profile and CV.
*   **Dashboard:** specialized dashboard to view applied jobs and save jobs for later.
*   **Profile Management:** Update personal information and resume details.

### 🏢 For Employers
*   **Post Jobs:** Create detailed job listings (Title, Description, Location, Salary).
*   **Manage Listings:** Edit or delete existing job posts.
*   **Applicant Tracking:** View a list of candidates who applied for specific posts.
*   **CV Download:** Download applicant CVs directly for offline review.

### 🛡️ System & Security
*   **Authentication:** Secure PHP-based login/logout sessions.
*   **Session Management:** Protected routes ensuring only authorized users access specific pages.
*   **Role-Based Access:** Distinct interfaces for Admins, Employers, and Job Seekers.

---

## 🛠️ Tech Stack

*   **Frontend:** HTML5, CSS3, JavaScript (Slick Slider, Responsive Design).
*   **Backend:** PHP (Server-side scripting).
*   **Database:** MySQL (Relational Data Management).
*   **Server:** Apache (via XAMPP).

---

## 📂 Directory Structure

```text
Learners-Hot-desk/
├── Code/
│   ├── assets/            # CSS, JS, Fonts, and Images
│   ├── config.php         # Database connection settings
│   ├── project_jobportal.sql # Old Main Database file
│   ├── index.php          # Landing page
│   ├── login.php          # Authentication
│   ├── dashboard.php      # User dashboard
│   ├── chat.php
│   ├── chat_handler.php
│   ├── config.php
│   ├── dashboard.php
│   ├── fix_session.php
│   ├── footer.php
│   ├── header.php
│   ├── job-applicants.php
│   ├── job-applied.php
│   ├── job-detail.php
│   ├── jobs.php
│   ├── Learners-Hot-desk.sql
│   ├── login.php
│   ├── logout.php
│   ├── post-job.php
│   ├── register.php
│   ├── report.php
│   ├── saved-jobs.php
│   ├── sql_schema.sql
│   ├── verify.php
├── Report/                # Project documentation and diagrams
│   ├── Project_Report_479.pdf
└── README.md

```
## ⚙️ Installation & Setup Guide

### 1. Prerequisites
*   You must have **XAMPP** (or a similar local server environment like WAMP/MAMP) preinstalled on your desktop.
*   Ensure **Apache** and **MySQL** ports are available (default ports 80/443 and 3306).

### 2. File Deployment
1.  Download the repository as a ZIP file.
2.  Extract the contents of the `Code` folder into your XAMPP `htdocs` directory.
    *   *Typical Path:* `C:\xampp\htdocs\Learners-Hot-desk`

### 3. Database Configuration
1.  Open the **XAMPP Control Panel** and start **Apache** and **MySQL**.
2.  Open your browser and navigate to `http://localhost/phpmyadmin/`.
3.  Click on the **Databases** tab.
4.  Create a new database named strictly: **`project_jobportal`**
5.  Select the created database and click the **Import** tab.
6.  Choose the `project_jobportal.sql` file (located in the root of the source code) and click **Go**.

### 4. Applying Constraints (Crucial Step)
To ensure the "Saved Jobs" functionality works correctly with cascading deletes, you must manually run the constraint query.

1.  In phpMyAdmin, select the `project_jobportal` database.
2.  Click on the **SQL** tab.
3.  Copy and paste the following command block and click **Go**:

# 👥 Contributors

This project, **"Learners’ Hot-desk"**, was developed by **The FrontEnders** team as part of the **CSE479 (Web Programming)** course at **East West University**.

### 👨‍💻 Team Members

| Student Name | Student ID |
| :--- | :--- |
| **Sayma Sultana** | 2022-1-60-405 |
| **Aditya Debnath** | 2022-2-60-124 |
| **Afia Tabassum** | 2023-1-60-091 |

<br>

### 🎓 Academic Details

*   **Course:** CSE479 (Section 2)
*   **Department:** Computer Science and Engineering
*   **Institution:** East West University

<br>

### 📝 Submitted To

**Md. Arman Hossain**  
Lecturer  
Department of Computer Science and Engineering  
East West University
