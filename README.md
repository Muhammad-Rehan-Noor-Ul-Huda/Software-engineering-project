# 🎓 University Complaint Management System (UCMS)

> **Course:** Software Engineering  
> **Institution:** University of the Punjab (PUCIT / FCIT)  
> **Submitted To:** Sir Anzar Ahmed  

---

## 📖 Project Overview
The **University Complaint Management System (UCMS)** is a Java-based desktop application designed to digitize and streamline the complaint handling process within the university. [cite_start]It replaces traditional manual methods with a centralized platform, allowing students to submit issues efficiently and ensuring administrators can track and resolve them with accountability [cite: 100-106].

### 🎯 Key Objectives
* [cite_start]**Centralization:** A single platform for all academic, administrative, and facility complaints[cite: 106].
* [cite_start]**Role-Based Access:** Secure, distinct dashboards for Students and Administrators[cite: 113].
* [cite_start]**Data Integrity:** Input validation to prevent empty or erroneous submissions[cite: 112].
* [cite_start]**OOP Implementation:** Demonstrates core software engineering principles like Layered Architecture and MVC [cite: 132-134].

---

## 🚀 Features

### 👤 For Students
* [cite_start]**Secure Login:** Authentication using unique User ID and Password[cite: 171].
* [cite_start]**Submit Complaint:** Easy-to-use interface to draft and submit complaints with titles and descriptions[cite: 201].
* [cite_start]**Validation:** Real-time checks to ensure no empty data is submitted [cite: 222-223].

### 🛠 For Admins
* [cite_start]**Dashboard Access:** Exclusive view for authorized personnel only[cite: 231].
* [cite_start]**View All Complaints:** Retrieve and view a complete list of submitted complaints from memory[cite: 237].
* [cite_start]**Status Management:** System architecture supports tracking complaint resolution status (e.g., "Submitted" vs "Resolved")[cite: 242].

---

## 🛠 Tech Stack
* [cite_start]**Language:** Java (JDK 8+)[cite: 128].
* [cite_start]**GUI Framework:** Java Swing[cite: 129].
* [cite_start]**Data Storage:** In-Memory (ArrayList / Repository Pattern)[cite: 369].
* [cite_start]**IDE:** IntelliJ IDEA / Eclipse / NetBeans[cite: 471].

---

## 🏗 System Architecture
[cite_start]The project is built using a **Layered Architecture** to ensure modularity and maintainability[cite: 375]:

1.  **Presentation Layer (View):** `LoginUI.java`, `StudentUI.java`, `AdminUI.java`.
2.  **Business Logic Layer (Controller):** `AuthController.java`, `ComplaintController.java`.
3.  **Data Layer (Model):** `User.java`, `Complaint.java`, `ComplaintRepository.java`.

### Domain Entities
* **User:** Base class for authentication attributes.
* **Student / Admin:** Specialized classes inheriting from User.
* [cite_start]**Complaint:** Stores ID, Title, Description, and Status[cite: 381].

---

## ⚙️ How to Run
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/UCMS-Project.git](https://github.com/your-username/UCMS-Project.git)
    ```
2.  **Open in IDE:** Import the folder into IntelliJ IDEA, Eclipse, or NetBeans.
3.  **Compile:** Ensure all `.java` files are compiled without errors.
4.  [cite_start]**Run:** Execute the **`LoginUI.java`** file to start the application[cite: 474].

---

## 🔐 Test Credentials
Use the following hardcoded credentials to test the different roles:

| Role | User ID | Password | Permissions |
| :--- | :--- | :--- | :--- |
| **Student** | `student` | *(Check AuthController.java)* | Submit Complaints |
| **Admin** | `admin` | *(Check AuthController.java)* | View/Manage Complaints |

---

## 📸 Diagrams
* [cite_start]**Use Case Diagram:** Defines actor interactions (Login, Submit, View)[cite: 250].
* [cite_start]**Domain Model:** Shows relationships between User, Student, Admin, and Complaint entities[cite: 283].
* [cite_start]**Activity Diagram:** Visualizes the flow of logic from Login to Complaint Submission[cite: 300].

---

## 👥 Development Team
[cite_start]**Group Members:** [cite: 84]

1.  **Haseeb Ahmad** (Roll No: BITF24M001)
2.  **M. Rehan** (Roll No: BITF24M014)
3.  **M. Khubaib** (Roll No: BITF24M037)

---

### 📝 License & Disclaimer
This project was developed for the **Software Engineering** semester project at **Punjab University**. It is intended for educational purposes and academic demonstration.
