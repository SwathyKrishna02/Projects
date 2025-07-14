# 🧑‍🏫 Class Committee Management System (CCMS)

A web-based application developed to streamline class committee operations in college departments. It automates scheduling, attendance tracking, report submissions, and student performance evaluations, providing a centralized platform for HODs, Class Committee Chairs (CC-Chairs), Faculty, and Student Representatives.

---

## 📌 Table of Contents
- [📚 Introduction](#-introduction)
- [🚀 Features](#-features)
- [🧩 Modules](#-modules)
- [🧑‍💻 System Roles](#-system-roles)
- [🛠️ Technologies Used](#-technologies-used)
- [📐 Data Flow Diagrams](#-data-flow-diagrams)
- [🎯 Use Case Diagram](#-use-case-diagram)
- [🧭 Process Workflow](#-process-workflow)
- [📸 Screenshots](#-screenshots)
- [🖥️ Requirements](#-requirements)
- [📄 License](#-license)
- [🧠 Topics](#-topics)
- [👩‍💻 Authors](#-authors)

---

## 📚 Introduction

The Class Committee Management System (CCMS) enables role-based management of class committee tasks, bringing transparency, efficiency, and automation into the academic workflow.

### 🗓️ Meeting Structure (Per Semester):
- **Zeroth Meeting** – Upload Course Plan & Evaluation Policy
- **First Meeting** – General Discussion
- **Midterm Meeting** – Submit Excel-based Midterm Marksheets
- **Internal Finalization** – Upload updated marks and reports
- **Grade Finalization** – Submit & generate final grade reports

🔔 Features like **automated email reminders**, **file parsing**, **graphical analytics**, and **versioned uploads** help ensure timely and accurate academic operations.

---

## 🚀 Features

- ✅ Role-based Access Control (HOD, CC-Chair, Faculty, Student)
- ✅ Automated Email Reminders (12 hours before submission deadlines)
- ✅ Secure File Uploads (.xlsx, .pdf)
- ✅ Graph Generation from Excel Sheets (Min, Max, Avg, Outliers)
- ✅ Version Control for Files
- ✅ Live Meeting Tracking and History
- ✅ Class-wise and Course-wise Folder Management
- ✅ Real-time Document Status Checks by CC-Chair

---

## 🧩 Modules

| Module | Description |
|--------|-------------|
| 🏛️ **HOD Dashboard** | Assign CC-Chairs, manage faculty and batches |
| 🧑‍🏫 **CC-Chair Panel** | Schedule meetings, send reminders, track uploads |
| 👨‍🎓 **Faculty Portal** | Upload course plans, marksheets, attendance reports |
| 👩‍🎓 **Student Panel** | View meeting minutes and performance summaries |
| 📊 **Graph Generator** | Convert Excel marksheets to analytical visuals |
| 🗂️ **File System** | Department → Batch → Group → Course → Files |

---

## 🧑‍💻 System Roles

### 👤 HOD (Admin)
- Add Batches & Faculty
- Assign Class Committee Chairs
- View Meeting & Upload Reports

### 👩‍💼 Class Committee Chair
- Schedule Meetings
- Add Faculty & Student Reps
- Send Reminders
- Track Submission Status

### 👨‍🏫 Faculty
- Upload Course Plans & Exam Results
- Submit Attendance & Grade Sheets
- Participate in Meetings

### 👩‍🎓 Student Representative
- Attend Meetings
- View Approved Reports (with permission)

---

## 🛠️ Technologies Used

| Category       | Tech Stack         |
|----------------|--------------------|
| Frontend       | HTML, CSS, JavaScript |
| Backend        | PHP                |
| Database       | MySQL              |
| File Processing| PHPExcel (.xlsx)   |
| Tools          | XAMPP, GitHub      |
| Hosting        | Localhost / Web Server |

---

## 📐 Data Flow Diagrams

### 🔁 Level 0 – Overview DFD  
![Level 0 DFD](./Images/DFD%20Level%200.png)

### 🔄 Level 1 – Detailed Process Flow  
![Level 1 DFD](./Images/DFD%20Level%201.png)

---

## 🎯 Use Case Diagram  
Defines interactions between roles and system functionalities.

![Use Case Diagram](./Images/Overview%20DFD.png)

## 🧩 Modules

| Module                | Description |
|------------------------|-------------|
| 🏛️ HOD Dashboard        | Assign CC-Chairs, add faculties, manage batches |
| 🧑‍🏫 CC-Chair Panel     | Schedule meetings, send reminders, manage uploads |
| 👨‍🎓 Faculty Portal     | Upload files (course plans, marks, attendance), respond to alerts |
| 👩‍🎓 Student Panel      | View approved meeting notes, grade summaries |
| 📊 Graph Generator      | Convert Excel mark sheets into visual reports |
| 🗂️ File System Manager  | Department → Batch → Group → Course → Files |

---

## 🧑‍💻 System Roles

### 👤 HOD (Admin)
- Add batches and faculties  
- Assign CC-Chairs  
- View summary reports

### 👩‍💼 CC-Chair
- Manage class committee groups  
- Schedule & monitor meetings  
- Remind faculty for submissions

### 👨‍🏫 Faculty
- Upload PDFs & Excel files  
- Submit grade and attendance reports  
- View generated graphs and performance data

### 👩‍🎓 Student Representative
- Attend meetings  
- View approved minutes and grades *(if access is granted)*

---

## 🛠️ Technologies Used

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: PHP  
- **Database**: MySQL  
- **File Processing**: PHPExcel (.xlsx parsing)  
- **Tools**: XAMPP, GitHub  
- **Hosting**: Localhost or Web server

---

## 📐 Data Flow Diagrams

These diagrams illustrate how data flows between users and internal modules.

### 🔁 Level 0 – Overview DFD  
![Level 0 DFD](./Images/DFD%20Level%200.png)

### 🔄 Level 1 – Detailed Process Flow  
![Level 1 DFD](./Images/DFD%20Level%201.png)

### 🧭 Process Workflow  
![Process Workflow](./Images/Process%20Workflow.png)

---

## 📸 Screenshots

### 🎓 Student Portal Interface  
![Student Portal](./Images/Student%20Portal.png)

### 📊 Graphical Mark Report  
![Graph Report](./Images/Graph%20Report.png)

### 📝 Grade Sheet Examples  
![Grade Sheet](./Images/Grade%20Sheet.png)  
![Marksheet 1](./Images/Marksheet1.png)  
![Marksheet 2](./Images/Marksheet2.png)

---

## 🖥️ Requirements

### 🧪 Software
- Modern browser (Chrome, Firefox)
- Web server (XAMPP or Apache)
- PHP ≥ 7.x
- MySQL

### 🖱️ Hardware
- Multi-core processor for smooth execution
- Stable internet connection (for hosted version)

---

## 📄 License

This project is licensed under the [Apache-2.0 License](LICENSE).

---

## 🧠 Topics

`php` `web-development` `front-end-development` `back-end-development`  
`student-portal` `bca-major-project` `minor-project` `management-system` `ccms`

---

## 👩‍💻 Authors

**👥 This is a Group Project developed as part of BCA Major Project work.**

**Developed by:** Swathy Krishna  
GitHub: [@SwathyKrishna02](https://github.com/SwathyKrishna02)

> ⭐ If you found this project helpful or inspiring, please star 🌟 the repository and follow for more!

---
