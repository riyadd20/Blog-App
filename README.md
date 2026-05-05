# Blog App

This is a Django-based blog application that supports multiple users, role-based access, and post management. Users can sign up, log in, and create or manage blog posts through a dashboard.

The project focuses on structuring the backend properly and handling user access across different roles.

---

## Features

* User signup and login
* Role-based access (admin, author, reader)
* Create, update, and delete blog posts
* Dashboard for managing posts
* Basic content display on the home page

---

## How it works

* Django handles the backend using its MVC (MVT) structure
* Authentication is session-based
* Users are assigned roles to control access to features
* Posts are stored in a relational database and displayed on the frontend

---

## Tech Stack

* Python
* Django
* MySQL
* Bootstrap
* JavaScript

---

## Project Structure

```text
Blog-App/
├── manage.py
├── miniblog/
│   ├── settings.py
│   ├── urls.py
│   └── ...
├── blog/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── templates/
│   └── static/
└── README.md
```

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
```

---

### 2. Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate
```

---

### 3. Install dependencies

```bash
pip install django mysqlclient
```

---

### 4. Configure database

Update your database settings in `settings.py` to use MySQL.

---

### 5. Run migrations

```bash
python manage.py migrate
```

---

### 6. Start the server

```bash
python manage.py runserver
```

Open:

```
http://127.0.0.1:8000/
```
