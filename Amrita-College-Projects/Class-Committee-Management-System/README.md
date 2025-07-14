# 🧑‍🏫 Class Committee Management System (CCMS)

A web-based application built to streamline the management of class committee operations within a college department. This system automates class committee meeting schedules, report submissions, attendance tracking, and student performance evaluations — bringing faculty, student representatives, and department administrators under one platform.

---

## 📌 Table of Contents
- 📚 [Introduction](#-introduction)
- 🚀 [Features](#-features)
- 🧩 [Modules](#-modules)
- 🧑‍💻 [System Roles](#-system-roles)
- 🛠️ [Technologies Used](#-technologies-used)
- 📐 [Data Flow Diagrams](#-data-flow-diagrams)
- 📸 [Screenshots](#-screenshots)
- 🖥️ [Requirements](#-requirements)
- 📄 [License](#-license)
- 🧠 [Topics](#-topics)
- 👩‍💻 [Authors](#-authors)

---

## 📚 Introduction

The **Class Committee Management System (CCMS)** enables HODs, Class Committee Chairs (CC-Chairs), Faculties, and Student Representatives to manage their responsibilities in an organized and automated manner.

Each semester includes five scheduled class committee meetings:
- **Zeroth Meeting** – Course plan & evaluation policy upload
- **First Meeting** – General review
- **Midterm Meeting** – Excel mark upload, graph generation
- **Internal Finalization** – Updated mark reports
- **Grade Finalization** – Grade sheet upload & conversion

> 🔔 Built-in features include automated reminders, file uploads, Excel data parsing, and graphical mark analytics.

---

## 🚀 Features

✅ Role-based access (HOD, CC-Chair, Faculty, Student)  
✅ Class-wise and course-wise file structure  
✅ Automated email reminders to faculty (12 hours before deadline)  
✅ Excel upload → Graph generator → Min/Max/Avg/Outlier detection  
✅ Document submission and status tracking  
✅ Meeting scheduling with calendar views  
✅ Graph-based mark reports and student performance analysis  
✅ Secure data access control and file versioning

---

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

Developed by: **Swathy Krishna**  
GitHub: [@SWATHY-KRISHNA](https://github.com/SwathyKrishna)

---

⭐ *If you find this project helpful or inspiring, give it a ⭐ star and consider following the repository!*
