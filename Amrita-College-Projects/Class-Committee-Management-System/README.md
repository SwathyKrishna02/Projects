# 🏫 Class Committee Management System (CCMS)

A web-based system designed to efficiently manage class committee operations in a college environment. The system automates meeting schedules, manages academic documents, facilitates communication between faculty and students, and generates graphical performance reports — enabling HODs, Class Committee Chairs, faculty members, and student representatives to collaborate on a unified platform.

---

## 📚 Introduction

The **Class Committee Management System** supports streamlined, semester-wise academic supervision. The HOD serves as the system admin, assigning Class Committee Chairs (CC-Chairs) to each batch. CC-Chairs then manage their respective groups, including course instructors, non-instructing faculty, and student representatives. The system simplifies the flow of document uploads, meeting coordination, and performance evaluations.

### 🗓️ Semester-wise Meeting Structure:
- **Zeroth Meeting** – Upload course plan & evaluation policy
- **First Meeting** – General academic review
- **Midterm Meeting** – Upload Excel mark sheets → Graphical analysis
- **Internal Finalization Meeting** – Upload updated mark sheets
- **Grade Finalization Meeting** – Upload Excel to generate grade reports

---

## 🧩 Problem Statement

Managing academic documents and committee meetings across multiple batches can become tedious without a systemized approach. This project provides a centralized file structure (Department > Batch > Group > Course > Faculty > File) and a role-based workflow. It ensures:

- Timely submission of course documents
- Automated and manual file reminders
- Organized meeting scheduling and attendance tracking
- Generation of analytical reports from uploaded Excel mark sheets

---

## 🧑‍💻 User Roles & Functionalities

### 👤 Head of Department (HOD)
- Add batches and faculty members
- Assign CC-Chairs to batches
- Oversee meeting summaries and uploaded files

### 👩‍💼 Class Committee Chair (CC-Chair)
- Add group members (faculty, students)
- Schedule meetings and send reminders
- Manage document submissions and access
- Track file status and control visibility

### 👨‍🏫 Faculty
- Upload course plans, mark reports, and attendance
- Attend class committee meetings
- View graphs and performance summaries

### 👩‍🎓 Student Representatives
- Participate in class committee meetings
- View approved reports and grade sheets (if permitted)

---

## ✨ Features

- ✅ Role-based access (HOD, CC-Chair, Faculty, Student)
- ✅ Excel Upload → Graph Generator (Min, Max, Avg, Outliers)
- ✅ Secure file storage and version control
- ✅ Automatic file reminders (12 hours before deadline)
- ✅ Real-time file status checks
- ✅ PDF uploads for evaluation policy and attendance
- ✅ Dynamic meeting scheduling and history tracking

---

## 🛠️ Technologies Used

| Category         | Stack                    |
|------------------|---------------------------|
| **Frontend**     | HTML, CSS, JavaScript     |
| **Backend**      | PHP                       |
| **Database**     | MySQL                     |
| **Tools**        | XAMPP, GitHub             |
| **File Parsing** | PHPExcel (.xlsx support)  |
| **Hosting**      | Localhost / Web Server    |

---

## 📐 System Architecture & Flow

### 🔁 Level 0 – DFD Overview  
![DFD Level 0](./images/dfd_level_0.png)

### 🔄 Level 1 – Detailed Flow  
![DFD Level 1](./images/dfd_level_1.png)

---

## 🧭 Use Case Diagram  
![Use Case Diagram](./images/overview_usecase.png)

Roles like HOD, CC-Chair, Faculty, and Students interact with various use cases such as login, upload, schedule, and attend meetings.

---

## 🔄 Process Workflow  
![Process Workflow](./images/process_workflow.png)

A step-by-step visual guide to understand how meetings and document flows are handled in the system.

---

## 📸 Screenshots

### 🎓 Student Portal  
![Student Portal](./images/student_portal.png)

### 📊 Graphical Mark Report  
![Graph Report](./images/graph_report.png)

### 📝 Grade Sheets  
![Grade Sheet](./images/grade_sheet.png)  
![Marksheet 1](./images/marksheet1.png)  
![Marksheet 2](./images/marksheet2.png)

---

## 📋 Requirements

### 🔧 Software:
- PHP ≥ 7.x
- MySQL
- Browser: Chrome / Firefox
- Web server: Apache (XAMPP recommended)

### 🖥️ Hardware:
- Multi-core processor
- Reliable internet (for live hosting)

---

## 🚀 Deployment

1. Clone the repo or download ZIP  
2. Extract to `htdocs` (XAMPP)  
3. Import `classcommitteedb.sql` in phpMyAdmin  
4. Start Apache & MySQL  
5. Access via: `http://localhost/Class-Committee-Management-System/`

---

## 📄 License

This project is licensed under the **Apache-2.0 License**.

---

## 👥 Group Project

This system was developed as part of the **BCA Major Project** for the academic year 2023–24.

---

## 🧠 Topics

`php` `web-development` `student-portal` `back-end-development` `management-system` `class-committee` `ccms` `bca-major-project`

---

⭐ If you found this project helpful or inspiring, please give it a ⭐ star and follow the repository!
