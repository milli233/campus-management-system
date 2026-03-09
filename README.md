# Smart Campus Management System (College ERP)

A web-based **College ERP System** developed using **Django (Python)** that helps manage academic and administrative activities within a college. The system allows administrators, faculty, and students to efficiently manage information such as student records, timetables, attendance, and course details through a centralized platform.

## 🚀 Features

* Student Management
* Faculty Management
* Class and Department Management
* Timetable Management
* Attendance Tracking
* Secure Authentication System
* Admin Dashboard
* Role-based access for Students and Faculty

## 🛠️ Tech Stack

* **Backend:** Python, Django
* **Frontend:** HTML, CSS, Bootstrap
* **Database:** SQLite
* **Version Control:** Git & GitHub

## 📂 Project Structure

```
Smart-Campus-Management-System
│
├── CollegeERP/
│
├── info/
│   ├── templates/
│   ├── static/
│
├── apis/
│
├── manage.py
└── db.sqlite3
```

## ⚙️ Installation & Setup

Follow these steps to run the project locally:

1. Clone the repository

```
git clone https://github.com/yourusername/smart-campus-management-system.git
```

2. Navigate to the project directory

```
cd COLLEGE-ERP
```

3. Install dependencies

```
pip install -r requirements.txt
```

4. Run migrations

```
python manage.py migrate
```

5. Start the development server

```
python manage.py runserver
```

6. Open the project in browser

```
http://127.0.0.1:8000
```

## 👤 User Roles

### Admin

* Manage students and faculty
* Create and manage timetable
* Monitor academic data

### Student

* View timetable
* Access academic information
* View attendance

### Faculty

* Manage attendance
* View assigned classes
* Update academic records

## 🔐 Authentication

The system uses Django’s built-in authentication system for secure login and logout functionality.

## 📈 Future Improvements

* Online assignment submission
* Internal marks management
* Email notifications
* Student performance analytics
* REST API integration

## 📄 License

This project is developed for educational purposes and academic learning.

---

⭐ If you like this project, feel free to give it a star on GitHub.
