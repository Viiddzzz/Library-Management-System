# 📚 Library Management System
A Python-based Library Management System using Tkinter and SQLite. Allows users to add, update, delete, and manage book records with real-time status tracking, search, and availability control all through a simple GUI interface.


**📘 Project Overview**
This project is a **Library Management System** built using **Python**, **Tkinter**, and **SQLite**.  
It provides an easy-to-use graphical interface for managing book records, including adding new books, issuing and returning books, and updating book details.  



## 🚀 Features

- Add new books to the database  
- Update existing book details  
- Delete individual or all records  
- Issue or return books dynamically  
- Change book availability status  
- View complete book inventory in a table  
- SQLite database integration for data storage  
- User-friendly Tkinter GUI with blue color theme  

---

## 🧠 Technologies Used

| Component | Description |
|------------|-------------|
| **Python** | Core programming language |
| **Tkinter** | GUI library for window design |
| **SQLite3** | Lightweight database for storage |
| **ttk Treeview** | For table-style book inventory display |

---

## 🎨 Interface Color Theme

| Section | Color | Description |
|----------|--------|-------------|
| Left Frame | yellow | Input section |
| Right Top | yellow | Action buttons |
| Right Bottom | DodgerBlue | Book inventory header |
| Buttons/Header | SteelBlue | Highlighted UI elements |

---

## 📂 Project Structure

Library-Management-System/
│
├── library_management.py # Main program file

├── library.db # Auto-created database file

├── README.md # Project documentation

└── requirements.txt # Dependencies (if needed)



## 🧩 How to Run

1. **Install Python** (version 3.8 or above).  
2. Install Tkinter (comes pre-installed with Python).  
3. Save the above code as `library_management.py`.  
4. Open terminal or command prompt and run:
   ```bash
   python library_management.py


**🗄️ Database Info**

The system automatically creates a SQLite database named library.db with the following table:

Column	Type	Description

BK_NAME	TEXT	Book Name

BK_ID	TEXT (Primary Key)	Unique Book ID

AUTHOR_NAME	TEXT	Author’s Name

BK_STATUS	TEXT	Available / Issued

CARD_ID	TEXT	Issuer’s Card ID



**🧰 Future Enhancements**

Add search and filter options

Generate issue-return history report

Add student/member management

Integrate with QR/barcode system



👨‍💻 Author Vidyashree s

🎓 Student Project | Python Tkinter GUI App

📧 vidyaa1103@gmail.com
