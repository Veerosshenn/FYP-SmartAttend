# SmartAttend – Smart Attendance Monitoring System (FYP)

## Project Overview

**SmartAttend** is a web-based Smart Attendance Monitoring System developed as a Final Year Project (BIT305) to modernize and automate attendance tracking in educational institutions. The system replaces traditional roll calls and QR-based attendance methods with a more accurate, secure, and interactive digital solution.

The platform integrates location-based attendance, quiz-based verification, digital MC submission, real-time notifications, analytics dashboards, and administrative reporting to improve efficiency, data accuracy, and student accountability.

This project was developed using Agile (Scrum) methodology across multiple iterations, focusing on scalability, usability, and real-time data management.

---

## Demo Video

https://github.com/user-attachments/assets/79eb1904-02fa-4dc6-9559-b50835fe7ccc

---

## Core Features (Final System)

### Authentication & Account Management

* Secure Sign Up & Login using Firebase Authentication
* Account Binding to prevent proxy attendance
* User Profile Management (view & update personal data)

### Location-Based Attendance Tracking

* GPS-based check-in verification
* Geofencing to ensure students are physically present in class
* Reduces proxy attendance and manual errors

### Quiz-Based Attendance Verification

* In-class quiz participation for attendance validation
* AI-generated quiz questions for engagement
* Lecturer-controlled quiz topic management

### Subject & Timetable Management

* Subject enrolment system for students
* Admin approval for subject registration
* Timetable creation stored in database
* Structured scheduling aligned with attendance tracking

### Medical Certificate (MC) Management

* Digital MC submission by students
* Admin approval / rejection workflow
* Automated attendance record updates after approval

### Attendance Analytics & Dashboard

* Profile dashboard with attendance trends and patterns
* Data visualization for student self-monitoring
* Real-time attendance insights for administrators

### Downloadable Attendance Reports

* Automated report generation
* Exportable attendance records for administrative use
* Reduces manual administrative workload

### Real-Time Notifications

* Attendance status alerts (warning / critical levels)
* MC approval notifications
* Attendance reminders using Firebase Cloud Messaging (FCM)

### Calendar Integration

* Sync class schedules with personal calendars
* Improves time management and attendance awareness

### Additional Smart Features

* Real-time attendance logging
* Secure cloud database storage
* Responsive web interface (desktop & mobile browsers)

---

## System Architecture

SmartAttend follows a secure web-based architecture:

* Client Layer: Students & Lecturers (Web Browsers)
* Web Server Layer: Handles requests & processing
* Firebase & MySQL Databases: Stores attendance, profiles, MCs, quizzes
* Cloud Services: Notifications, authentication, and analytics

The system uses layered security with authentication, database protection, and firewall-based architecture to ensure data integrity and scalability.

---

## Technologies & Tools Used

### Frontend

* HTML5, CSS3, JavaScript
* Responsive UI/UX Design
* Vite (Fast development build tool)

### Backend & Cloud

* Firebase Authentication (Secure login & account binding)
* Firebase Firestore (Real-time database)
* Google Cloud Functions (Backend logic & processing)
* EmailJS (Automated email notifications)

### Database

* Firebase Firestore (Real-time attendance & MC data)
* MySQL (Structured data storage)

### AI & APIs

* Hugging Face (AI-generated quiz questions)
* CoreLocation / GPS API (Location verification)
* Firebase Cloud Messaging (Push notifications)

### Testing & Development Tools

* Jest (Unit Testing)
* Jira (Project Management)
* Figma (Wireframing & UI Design)
* Agile Scrum Methodology

---

## Development Iterations (Agile Scrum)

### Iteration 1 (Core System)

* Sign Up & Login
* Profile Management
* Subject Enrolment & Approval
* Digital Attendance
* Timetable Database Creation

### Iteration 2 (System Expansion)

* Account Binding
* MC Submission & Approval
* Downloadable Attendance Reports
* Calendar Integration
* System Integration Testing

### Iteration 3 (Advanced Features)

* Quiz Topic Management
* AI-Generated Quizzes
* Attendance Status Notifications
* Attendance Analytics Dashboard

---

## My Contributions (Rosshen)

**Veerosshen A/L Vikneswaran (Rosshen)** – FYP Developer

Key Contributions:

* Location-Based Attendance Module (GPS & Geofencing)
* Account Binding Security Feature
* Attendance Analytics Dashboard & Profile Visualization
* Quiz-Based Attendance System Integration
* AI-Generated Quiz Feature (Integration Logic)
* Real-Time Attendance Notifications
* Firebase Integration (Authentication & Firestore)
* System Architecture Design & Database Structuring
* UI/UX Implementation for Core Attendance Interfaces
* Agile Sprint Development & Iteration Implementation

---

## Target Users

* Students – Mark attendance, submit MCs, track analytics
* Lecturers – Manage quizzes, monitor attendance, generate reports
* Administrators – Approve MCs, manage subjects, download reports
* University Management – View engagement insights & analytics

---

## Project Objectives

* Automate attendance tracking with higher accuracy
* Reduce administrative workload
* Prevent proxy attendance using account binding & location tracking
* Provide real-time insights and analytics
* Improve student engagement through interactive quiz-based verification

---

## System Limitations

* Requires stable internet connection
* Depends on GPS accuracy indoors
* Limited to web-based platform (no mobile app)
* No LMS integration (within project scope)

---

## Academic Information

Final Year Project (FYP II)
Bachelor of Information Technology (Hons)
Faculty of Computing and Digital Technology
HELP University – 2025

---

## License

This project is developed for academic purposes as part of a Final Year Project submission and is not intended for commercial distribution.
