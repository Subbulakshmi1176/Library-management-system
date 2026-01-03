📚 Library Management System (Java)

A console-based Library Management System developed using Core Java, Object-Oriented Programming (OOP) concepts, and File Handling.
This project allows Admin and Customer users to manage books, borrowing, and returning operations efficiently.

🚀 Features
👨‍💼 Admin

Add new books to the library

View all available books

Manage library records

View borrowing entries

👤 Customer

Login as customer

View available books

Borrow books

Submit/return books

🗂 Data Storage

Uses text files (.txt) for data persistence

No database required

Simple and lightweight

🛠️ Technologies Used
Technology	Purpose
Java (Core)	Application logic
OOP Concepts	Abstraction, Encapsulation
File Handling	Store & retrieve data
Git & GitHub	Version control
📁 Project Structure
Library-management-system/
│
├── 0entry.txt
├── 1entry.txt
│
├── AdminMenu.java
├── Book.java
├── BookManage.java
├── Customer.java
├── CustomerLogin.java
├── CustomerMenu.java
├── FileHandler.java
├── GetBook.java
├── GetInput.java
├── Main.java
├── Validation.java
├── entryManage.java
├── libraryEntry.java
├── show.java
├── submitBook.java
├── package-info.java
│
└── libpackage/          (generated after compilation)

📦 Package Information

All Java files belong to a single package:

package libpackage;


During compilation, Java automatically creates the libpackage folder.

▶️ How to Run the Project
🔹 Prerequisites

Java JDK 8 or above

Git (optional)

Command Prompt / PowerShell / Terminal

🔹 Step 1: Clone the Repository
git clone https://github.com/Subbulakshmi1176/Library-management-system.git

cd Library-management-system

🔹 Step 2: Compile the Project
javac -d . *.java


📌 This creates the libpackage directory with .class files.

🔹 Step 3: Run the Application
java libpackage.Main


🎉 The Library Management System will start.

🧠 How the Project Works

Main.java → Entry point of the application

Menu-driven flow using switch cases

Separate classes for Admin, Customer, Book, and File Handling

Data stored persistently using text files

Validation prevents incorrect input

🧩 Key Classes Explained
Class Name	Description
Main	Starts the application
AdminMenu	Admin operations
CustomerMenu	Customer operations
Book	Book model
Customer	Customer model
FileHandler	File read/write logic
Validation	Input validation
submitBook	Book return logic
🧪 Sample Output
===== Library Management System =====
1. Admin Login
2. Customer Login
3. Exit
Enter your choice:

🔐 Future Enhancements

Add database support (MySQL)

Create GUI using JavaFX or Swing

Implement authentication

Convert to Web Application

👩‍💻 Author

Subbu Lakshmi
📌 Java & Web Development Enthusiast
📌 Aspiring Software Engineer

📄 License

This project is for learning and educational purposes.

⭐ If you like this project

Give it a ⭐ on GitHub 😊