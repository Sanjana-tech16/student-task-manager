# 📝 Student Task Manager

> A full-stack web application designed to help students organize their daily tasks, assignments, and exams efficiently.

![Project Status](https://img.shields.io/badge/status-completed-success)
![Python](https://img.shields.io/badge/python-v3.12-blue)
![Flask](https://img.shields.io/badge/flask-v3.0-green)

## 🌟 Overview
Student Task Manager is a CRUD (Create, Read, Update, Delete) application built with **Flask** and **SQLite**. It features a modern, responsive UI designed with Bootstrap 5 and custom CSS, providing a seamless experience for managing personal to-do lists.

## ✨ Features
* **🔐 Secure Authentication:** User registration and login system with password hashing.
* **📋 Task Management:** Easily add, view, and delete tasks.
* **✅ Progress Tracking:** Mark tasks as "Done" with visual strikethrough indicators.
* **🎨 Modern UI:** Glassmorphism design, gradient backgrounds, and interactive hover effects.
* **📱 Responsive:** Works perfectly on mobile and desktop devices.
* **💾 Data Persistence:** Uses SQLite for reliable local data storage.

## 🛠️ Tech Stack
* **Backend:** Python, Flask, SQLAlchemy
* **Frontend:** HTML5, CSS3, Bootstrap 5, Jinja2 Templating
* **Database:** SQLite
* **Icons:** FontAwesome 6

## 📂 Project Structure
```text
student-task-manager/
├── instance/
│   └── database.db      # SQLite Database
├── static/
│   └── style.css        # Custom styling
├── templates/
│   ├── base.html        # Master layout
│   ├── index.html       # Dashboard
│   ├── login.html       # Login Page
│   └── register.html    # Registration Page
├── app.py               # Main Application Logic
├── setup_db.py          # Database Initialization Script
└── requirements.txt     # Project Dependencies

#SANJANA S - B TECH IT