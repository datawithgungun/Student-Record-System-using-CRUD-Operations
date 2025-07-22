# Student-Record-System-using-CRUD-Operations
A simple Python-MySQL project to manage student records with insert, view, update, and delete operations via a CLI menu.   
Here's a clean and professional **README.md** content for your GitHub project:

---

# 🧑‍🎓 Student Record Management System (Python + MySQL)

A simple command-line-based Student Record Management System built using **Python** and **MySQL**. This project allows you to perform basic CRUD operations such as adding, displaying, updating, and deleting student records from a MySQL database.

---

## 📌 Features

* 📥 Insert new student records
* 📋 Display all student data
* ✏️ Update student grades
* ❌ Delete student records
* 💾 MySQL database integration
* 🔁 Loop-based main menu for continuous use

---

## 🛠️ Technologies Used

* **Python**
* **MySQL**
* **mysql-connector-python** library

---

## 🧾 Requirements

* Python 3.x
* MySQL Server
* `mysql-connector-python` package
  *(Install via: `pip install mysql-connector-python`)*

---

## 🔧 Setup Instructions

1. **Create a MySQL Database and Table:**

```sql
CREATE DATABASE school;

USE school;

CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    age INT,
    grade VARCHAR(10)
);
```

2. **Clone this repository and run the script:**

```bash
python student_records.py
```

---

## 🧑‍💻 Project Structure

```python
- get_connection()          # Establishes MySQL connection
- insert_student()          # Inserts student data into database
- display_students()        # Displays all student records
- update_grade()            # Updates a student’s grade by ID
- delete_student()          # Deletes a student record by ID
- main()                    # Main menu loop
```

---

## 📷 Demo

![Student Record System Demo](https://via.placeholder.com/700x300?text=Console+Demo+of+Student+Record+System)
![Sql Student Table](https://github.com/user-attachments/assets/7d4aa8cd-7a00-41f8-b1c3-d28bf7ad7e84)
![SQl ater delete](https://github.com/user-attachments/assets/9f3c2518-7fd7-43e4-85f1-599962bbb749)

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---
