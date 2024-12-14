# 🌐 CSWALA - Web-Based Learning Platform

CSWALA is a web-based interactive learning platform designed to empower individuals in programming and web development. With a user-friendly interface, real-time coding environments, and structured courses, it bridges the gap between theoretical knowledge and practical application.

---

## 📖 **Project Overview**
- **Platform**: Provides an engaging learning environment with features like course management, student progress tracking, and real-time coding exercises.
- **For Educators**: Enables course creation, management, and monetization for instructors.
- **Scalability**: Designed for future enhancements, including AI-driven recommendations, advanced analytics, and multi-platform support.

---

## 🎯 **Objectives**
1. Develop a scalable database for managing teachers, students, admins, and courses.
2. Ensure data integrity with constraints, triggers, and transactions.
3. Provide mechanisms for tracking progress and payments.
4. Implement structured queries for reporting and analysis.

---

## 🚀 **Key Features**
- **Interactive Courses**: Real-time coding environments and practical exercises.
- **Progress Tracking**: Monitors student achievements and progress.
- **Payment System**: Handles course enrollments and transactions.
- **Triggers and Transactions**: Ensures data consistency and automated logging.
- **Community Forum**: Peer-to-peer learning and discussion space.

---

## 📂 **Database Schema**
The project uses a relational database designed with the following key tables:
- **Users**: Manages student and instructor information.
- **Courses**: Stores course details.
- **Enrollments**: Tracks student registrations and course completion.
- **Payments**: Logs transactions.
- **Feedback**: Records student feedback and ratings.
- **ProgressTracking**: Monitors student progress in courses.
- **AuditLogs**: Maintains a log of system actions for accountability.

### **Triggers**
- Automatically logs user actions (e.g., progress updates, payment failures).
- Ensures course completion status is updated based on student progress.

### **Stored Procedures**
- Automate complex queries, such as updating progress, enrolling students, and processing payments.

---

## 🛠️ **Tech Stack**
- **Backend**: MySQL/MariaDB
- **Frontend**: HTML, CSS, JavaScript (future integration with frameworks like React).
- **Development Tools**: XAMPP, phpMyAdmin.

---

## 📈 **Performance and Testing**
- **Data Integrity**: Maintained through foreign keys, constraints, and triggers.
- **Performance Optimization**: Query optimization techniques like indexing.
- **Scalability**: Tested with a limited user base, ensuring smooth operations.

---

## 💻 **Setup Instructions**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ovishkh/CSWALA-SQL.git
   cd CSWALA-SQL




## Database Setup:

1. **Import the SQL file into phpMyAdmin**:
   - Open XAMPP and start **Apache** & **MySQL**.
   - Navigate to [http://localhost/phpmyadmin/](http://localhost/phpmyadmin/).
   - Create a new database named `cswala`.
   - Import the provided SQL script to create tables and insert sample data.

## Run the Platform:

- Use any local server (e.g., **XAMPP**) to host the frontend files.
- Ensure the database connection is correctly configured in the backend.

---

## 🔍 **Future Enhancements**

- **AI-Driven Personalization**: Add machine learning to recommend courses and content.
- **Enhanced UI/UX**: Upgrade to modern frameworks like **React** or **Angular**.
- **Mobile App Support**: Build cross-platform mobile applications.
- **Advanced Analytics**: Implement real-time performance tracking.
- **Security Enhancements**: Implement advanced encryption techniques and ensure compliance with updated data protection regulations.
- **Performance Scalability**: Conduct comprehensive stress testing and optimize the system’s architecture.

---

## 🧑‍🤝‍🧑 **Team Members**

| Name                  | ID                  | Role                            |
|-----------------------|---------------------|---------------------------------|
| Shahriar N. Ovi       | 0242220005101824    | Triggers, Views, Procedures     |
| Kamrujjaman Tuhin     | 0242220005101815    | SQL Operators, Nested Queries   |
| Apra Rani Das         | 0242220005101823    | Data Entry, Testing             |
| Khalid Anwar Antur    | 0242220005101553    | Database Design                 |

---

## 📚 **References**

- **Fundamentals of Database Systems** by Ramez Elmasri & Shamkant B. Navathe.
- **SQL Queries for Dummies** by Allen G. Taylor.
- **Database Management Systems** by Raghu Ramakrishnan & Johannes Gehrke.
- **Introduction to Algorithms** by Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest, Clifford Stein.
- **Database System Concepts** by Silberschatz, A., Korth, H. F., & Sudarshan, S.

---

## **Explanation:**
1. **Project Overview**: Describes the purpose and features of the CSWALA platform.
2. **Objectives**: Lists the main goals achieved by the project.
3. **Key Features**: Highlights the primary functionalities and features of the platform.
4. **Database Schema**: Gives an overview of the tables used, with special focus on triggers and stored procedures.
5. **Tech Stack**: Specifies the technologies used for backend, frontend, and tools.
6. **Performance and Testing**: Mentions the importance of data integrity, performance optimization, and scalability.
7. **Setup Instructions**: Provides step-by-step instructions for setting up the project on a local machine using XAMPP.
8. **Future Enhancements**: Suggests potential future improvements and new features.
9. **Team Members**: Credits the contributors to the project.
10. **References**: Lists academic and reference books used for the project.

