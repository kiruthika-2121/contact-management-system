**Contact Management System**

The Contact Management System is a web-based application designed to efficiently store, manage, and retrieve contact details. 
This project was developed using Python (Flask framework), HTML, CSS, and MySQL as the database. 
The system provides a user-friendly interface that allows users to create, update, delete, and search for contacts effortlessly.
The primary goal of this project is to streamline the process of managing contact information in an organized and secure manner.

---

**Features**
1. Add New Contacts: Users can input new contact information, including name, email, phone number, and address.
2. View Contact List: A well-structured list of all contacts with an intuitive layout.
3. Search Contacts: Quick and efficient search functionality by name or other details.
4. Edit Contact Details: Users can update existing contact information.
5. Delete Contacts: Users can remove unwanted contacts from the system.

---

**Technologies Used**
Backend: Python with Flask framework for handling server-side logic.
Frontend: HTML and CSS for the user interface.
Database: MySQL for storing and managing contact data.

---

**Database Schema**
The database schema for the Contact Management System consists of a single table named contacts:
///CREATE DATABASE contact_management;

USE contact_management;

CREATE TABLE contacts (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    phone VARCHAR(15),
    email VARCHAR(100)
);///

**Run the Project**
1. Start the Flask app:
 Run the app.py file.
2. Visit " http://127.0.0.1:5000 " in your browser.

**Screenshots**
![Screenshot 2024-12-11 174351](https://github.com/user-attachments/assets/b1385ad0-a458-478f-890f-505651863b4f)

![Screenshot 2024-12-11 174445](https://github.com/user-attachments/assets/c28b2ba9-4556-4e0f-b5aa-bccfa5a78284)

![Screenshot 2024-12-11 174503](https://github.com/user-attachments/assets/cf0358e5-9b5d-4b34-9b5f-7dccbb5a192f)

****THANK YOU!!!****
