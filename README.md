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

## 📂 Project Structure

LibraryManagementSystem/
│
├── src/                      # Java source files
│   ├── library/              # Your Java packages
│   │   ├── Main.java
│   │   ├── DatabaseConnection.java
│   │   ├── Book.java
│   │   ├── Member.java
│   │   └── ...other classes
│   └── META-INF/             # Manifest files (if needed)
│
├── web/                      # JSP/HTML/CSS/JS files (if using web module)
│   ├── index.jsp
│   ├── style.css
│   └── script.js
│
├── nbproject/                 # NetBeans project configuration
│   ├── project.properties
│   ├── private/
│   └── ...
│
├── database/                  # Database export & related files
│   └── library.sql
│
├── lib/                       # External JAR dependencies (e.g., MySQL connector)
│   └── mysql-connector-java-8.x.x.jar
│
├── README.md                  # Project documentation (what we wrote earlier)
├── .gitignore                 # Git ignore rules (to skip build files, etc.)
├── pom.xml                    # Maven configuration (if Maven project)
└── build.xml                  # Ant build file (if Ant project)


---




