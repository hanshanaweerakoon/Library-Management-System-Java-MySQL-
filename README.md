# 📚 Library Management System

A Java-based Library Management System developed using *NetBeans* and *MySQL (WAMP Server)*.  
This application helps manage books, members, borrowing, and returns efficiently through a clean and user-friendly interface.

---

## 🚀 Features
- *Book Management*
  - Add new books
  - Search and update book details
- *Member Management*
  - Register new members
  - View and update member details
- *Borrow & Return*
  - Issue books to members
  - Return and update status
- *Inquiries & Reports*
  - Book inquiry
  - Member inquiry
  - Daily reports
  - Inquiry tables
- *Settings & User Control*
  - Logout
  - Admin settings

---

## 🖼 Screenshot
![Library Management System Dashboard](assets/dashboard.png)

(The screenshot above shows the main dashboard with all available operations.)

---

## 🛠 Technologies Used
- *Java (NetBeans IDE)*
- *MySQL (WAMP Server)*
- *JDBC* for database connectivity
- *Swing / JavaFX* for user interface (depending on your setup)

---


## 📥 Installation & Setup
1. **Clone the repository**
   bash
   git clone [https://github.com/hanshanaweerakoon/Library-Management-System-Java-MySQL-.git]
`

2. **Open in NetBeans**

   * Go to File → Open Project → Select the project folder.

3. **Database Setup**

   * Start WAMP Server.
   * Open `http://localhost/phpmyadmin`.
   * Create a new database (e.g., `library_db`).
   * Import `database/library.sql`.

4. **Configure Database Connection**
   Update your DB connection settings in the Java file:
'''
   String url = "jdbc:mysql://localhost/library_db";
   String user = "root";
   String pass = "";
'''

---




