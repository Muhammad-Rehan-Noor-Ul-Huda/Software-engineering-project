# 🎓 University Complaint Management System (UCMS)

> **Course:** Software Engineering  
> **Institution:** University of the Punjab (PUCIT / FCIT)  
> **Submitted To:** Sir Anzar Ahmed  

---

## 📖 Project Overview
The **University Complaint Management System (UCMS)** is a Java-based desktop application designed to digitize and streamline the complaint handling process within the university. It replaces traditional manual methods with a centralized platform, allowing students to submit issues efficiently and ensuring administrators can track and resolve them with accountability .

### 🎯 Key Objectives
* **Centralization:** A single platform for all academic, administrative, and facility complaints.
* **Role-Based Access:** Secure, distinct dashboards for Students and Administrators.
* **Data Integrity:** Input validation to prevent empty or erroneous submissions.
* **OOP Implementation:** Demonstrates core software engineering principles like Layered Architecture and MVC.

---

## 🚀 Features

### 👤 For Students
* **Secure Login:** Authentication using unique User ID and Password.
* **Submit Complaint:** Easy-to-use interface to draft and submit complaints with titles and descriptions.
* **Validation:** Real-time checks to ensure no empty data is submitted.

### 🛠 For Admins
* **Dashboard Access:** Exclusive view for authorized personnel only.
* **View All Complaints:** Retrieve and view a complete list of submitted complaints from memory.
* **Status Management:** System architecture supports tracking complaint resolution status (e.g., "Submitted" vs "Resolved").

---

## 🛠 Tech Stack
* **Language:** Java (JDK 8+).
* **GUI Framework:** Java Swing.
* **Data Storage:** In-Memory (ArrayList / Repository Pattern)
* **IDE:** IntelliJ IDEA / Eclipse / NetBeans

---

## 🏗 System Architecture
The project is built using a **Layered Architecture** to ensure modularity and maintainability

1.  **Presentation Layer (View):** `LoginUI.java`, `StudentUI.java`, `AdminUI.java`.
2.  **Business Logic Layer (Controller):** `AuthController.java`, `ComplaintController.java`.
3.  **Data Layer (Model):** `User.java`, `Complaint.java`, `ComplaintRepository.java`.

### Domain Entities
* **User:** Base class for authentication attributes.
* **Student / Admin:** Specialized classes inheriting from User.
* **Complaint:** Stores ID, Title, Description, and Status

---

## ⚙️ How to Run
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/UCMS-Project.git](https://github.com/your-username/UCMS-Project.git)
    ```
2.  **Open in IDE:** Import the folder into IntelliJ IDEA, Eclipse, or NetBeans.
3.  **Compile:** Ensure all `.java` files are compiled without errors.
4.  **Run:** Execute the **`LoginUI.java`** file to start the application.

---

## 🔐 Test Credentials
Use the following hardcoded credentials to test the different roles:

| Role | User ID | Password | Permissions |
| :--- | :--- | :--- | :--- |
| **Student** | `student` | *(Check AuthController.java)* | Submit Complaints |
| **Admin** | `admin` | *(Check AuthController.java)* | View/Manage Complaints |

---

## 📸 Diagrams
* **Use Case Diagram:** Defines actor interactions (Login, Submit, View).
* **Domain Model:** Shows relationships between User, Student, Admin, and Complaint entities.
* **Activity Diagram:** Visualizes the flow of logic from Login to Complaint Submission.

---

## 👥 Development Team
**Group Members:** 

1.  **Haseeb Ahmad** (Roll No: BITF24M001)
2.  **M. Rehan** (Roll No: BITF24M014)
3.  **M. Khubaib** (Roll No: BITF24M037)

---

### 📝 License & Disclaimer
This project was developed for the **Software Engineering** semester project at **Punjab University**. It is intended for educational purposes and academic demonstration.
