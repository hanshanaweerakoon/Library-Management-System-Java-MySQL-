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
Library Management System Dashboard <img width="1041" height="502" alt="Main Menu" src="https://github.com/user-attachments/assets/283792b5-5d46-496d-9285-41e580f1ff02" />


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
   git clone https://github.com/hanshanaweerakoon/Library-Management-System-Java-MySQL-.git

2. **Open in NetBeans**

   * Go to File → Open Project → Select the project folder.

3. **Database Setup**

   * Start WAMP Server.
   * Open `http://localhost/phpmyadmin`.
   * Create a new database (e.g., `library_db`).
   * Import `database/library.sql`.

4. **Configure Database Connection**
   Update your DB connection settings in the Java file:

```java
   String url = "jdbc:mysql://localhost/library_db";
   String user = root;
   String pass = "";
```
5. **Run the Project**

   * Press `F6` in NetBeans.

---

## 📸 More Screenshots

<img width="1366" height="768" alt="Login" src="https://github.com/user-attachments/assets/4facd57d-ee85-4ab9-a469-28891815fdb3" />

<img width="1366" height="768" alt="Books" src="https://github.com/user-attachments/assets/daca3442-d211-4a38-8731-dfb404554abc" />


<img width="1366" height="768" alt="Daily report" src="https://github.com/user-attachments/assets/6f3e0b8f-6a17-4edd-87a4-ba53dca79cfe" />

<img width="1366" height="768" alt="Inquiry" src="https://github.com/user-attachments/assets/1db64064-eec6-4f1a-b1c8-265497e51068" />

<img width="1366" height="768" alt="Members" src="https://github.com/user-attachments/assets/dde53842-39bf-4cc4-b114-58ab754fa204" />
