# 📝 E-Notes Management System

A web-based **E-Notes Management System** built using Django.
This application allows users to create, manage, update, and delete their notes from one place.

## 🚀 Features

* 👤 User Registration & Login
* 🔐 User Authentication
* 📝 Create Notes
* 👀 View Notes
* ✏️ Update Notes
* 🗑️ Delete Notes
* 📱 Responsive Interface
* 🔒 User-specific Notes
* 🗄️ Database Management using Django ORM

## 🛠️ Technologies Used

* 🐍 Python
* 🌐 Django
* 🎨 HTML
* 🎨 CSS
* ⚡ JavaScript
* 🗄️ SQLite / Database
* 🔧 Git & GitHub

## 📸 Screenshots

### 🏠 Home Page

![Home Page](screenshots/enotes.png)

### 🔐 Login Page

![Login Page](screenshots/login.png)

### 📝 Notes Dashboard

![Notes Dashboard](screenshots/dashboard.png)

### ✏️ Add / Update Note

![Add Note](screenshots/add-note.png)

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/SUKHVENDRAKUMAR/enotesupdate.git
```

### 2. Open the project

```bash
cd enotesupdate
```

### 3. Create virtual environment

```bash
python -m venv venv
```

### 4. Activate virtual environment

Windows:

```bash
venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run migrations

```bash
python manage.py migrate
```

### 7. Start the server

```bash
python manage.py runserver
```

Now open:

```text
http://127.0.0.1:8000/
```

## 📂 Project Structure

```text
enotesupdate/
│
├── manage.py
├── requirements.txt
├── db.sqlite3
│
├── project/
│   ├── settings.py
│   ├── urls.py
│   └── ...
│
├── app/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── ...
│
└── screenshots/
    ├── home.png
    ├── login.png
    ├── dashboard.png
    └── add-note.png
```

## 🎯 Purpose

The main purpose of this project is to provide a simple platform where users can securely manage their personal notes.

This project also demonstrates practical usage of:

* Django Models
* Django Views
* Django Templates
* URL Routing
* Forms
* Authentication
* CRUD Operations
* Database Operations

## 👨‍💻 Author

**Sukhvendra Yadav**

### 🔗 GitHub

https://github.com/SUKHVENDRAKUMAR
