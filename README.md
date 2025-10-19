# 🏦 Bank Management System with ATM Simulator 💳

A **Java-based Bank Management System** built using **NetBeans IDE** and **MySQL Workbench**, designed to simulate real-world banking operations and ATM functionality.
This project is part of the **BCA Final Year Project** and includes complete ER diagrams, database structure, and a project report.

---

## 📌 Project Overview

The **Bank Management System with ATM Simulator** allows users to:

* Create and manage bank accounts
* Deposit and withdraw money
* Check balances
* Simulate ATM operations (PIN verification, transaction, receipt)
* Manage customer and transaction data in MySQL

It is designed to replicate essential banking system functionalities with a **simple, user-friendly Java Swing interface**.

---

## ✨ Features

* 🧍 **User Registration & Login**
* 🏦 **Account Creation & Management**
* 💰 **Deposit & Withdrawal Operations**
* 🧾 **Balance Inquiry**
* 💳 **ATM PIN Verification System**
* 🕒 **Transaction History Tracking**
* 🛡️ **Secure Database Integration** using MySQL
* 📈 **Admin Panel** for managing all accounts

---

## 🛠️ Tech Stack

| Component              | Technology            |
| ---------------------- | --------------------- |
| 💻 Frontend            | Java Swing (NetBeans) |
| 🗄️ Backend            | MySQL Workbench       |
| 🧠 IDE                 | NetBeans              |
| 📝 Language            | Java (JDK 8+)         |
| 🔐 Database Connection | JDBC                  |

---

## 📂 Project Structure

```
ATM-Simulator-System/
 ├─ nbproject/
 ├─ src/
 │   └─ bankmanagement/   # Java source files
 ├─ dist/
 ├─ database/
 │   └─ bank_management.sql
 ├─ report/
 │   ├─ Project-Report.pdf
 │   └─ ER-Diagram.pdf
 ├─ README.md
 └─ .gitignore
```

---

## 📊 ER Diagram

📌 [View ER Diagram (PDF)](./My%20Project%20DFD%20Er.pdf)
*(Opens in GitHub PDF Viewer)*

---

## 📘 Project Report

📄 [Download Full Project Report (PDF)](./My%20Project%20Report.pdf)
Includes:

* Problem Definition
* Objective
* Existing & Proposed System
* System Design (DFD, ERD, Schema)
* Implementation Details
* Output Screenshots
* Conclusion

---

## 🧰 How to Run Locally

1. **Clone the Repository**

   ```bash
   git clone https://github.com/itsrekib/ATM-Simulator-System.git
   cd ATM-Simulator-System
   ```

2. **Import into NetBeans**

   * Open NetBeans → `File → Open Project`
   * Select the project folder

3. **Import the Database**

   * Open MySQL Workbench
   * Create a new schema (e.g., `bank_management`)
   * Import `database/bank_management.sql` file

4. **Update DB Credentials**

   * In the source code, update JDBC URL, username, and password as per your system

5. **Run the Project**

   * Click ▶️ **Run Project** in NetBeans

---

## 🖼️ Screenshots

| Login Page        | ATM Interface       | Dashboard        |
|------------------|-------------------|----------------|
| ![Login](./screenshots/Screenshot%202025-10-19%20234829.png) | ![ATM](./screenshots/Screenshot%202025-10-19%20234845.png) | ![Dashboard](./screenshots/Screenshot%202025-10-19%20234904.png) |

| Deposit          | Withdraw           | Balance         |
|-----------------|------------------|----------------|
| ![Deposit](./screenshots/deposit.png) | ![Withdraw](./screenshots/withdraw.png) | ![Balance](./screenshots/balance.png) |

| Transaction History | PIN Verification | Receipt        |
|-------------------|-----------------|----------------|
| ![History](./screenshots/transaction_history.png) | ![PIN](./screenshots/pin_verification.png) | ![Receipt](./screenshots/receipt.png) |

Viw All [Images](https://github.com/itsrekib/ATM-Simulator-System/tree/main/screenshots)
---

## ✍️ Author

👤 **Rekibur Uddin**
📧 [Your Email or Portfolio Link]
💻 BCA Final Year Project | Java Developer | Android Developer

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on [GitHub](https://github.com/itsrekib/ATM-Simulator-System) 🙌
