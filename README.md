![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Django](https://img.shields.io/badge/Django-4.x-darkgreen?logo=django)
![Database](https://img.shields.io/badge/Database-SQLite-blue)
![Status](https://img.shields.io/badge/Project-Active-success)
![License](https://img.shields.io/badge/License-MIT-yellow)
![GitHub repo size](https://img.shields.io/github/repo-size/your-username/djclass)
![GitHub last commit](https://img.shields.io/github/last-commit/your-username/djclass)

# DJClass – Django Classifieds Web Application

DJClass is a **Django-based classifieds web application** that allows users to register, log in, and post classified listings with detailed information such as category, brand, color, description, and images.  
The project follows Django’s **MVT (Model–View–Template)** architecture and is designed for learning and academic purposes.

---

## 🚀 Features

- User authentication (Register, Login, Logout)
- User profile management
- Create, update, and delete classified listings
- Categories, brands, colors, and detailed descriptions
- Image upload and media handling
- Like / favorite listings
- Search and filter functionality
- Django admin panel
- Responsive UI using Bootstrap

---

## 🏗 Project Structure

djclass/
|
├── manage.py
|
├── db.sqlite3

│
├── djclass/
│ ├── settings.py
│ ├── urls.py
│ ├── asgi.py
│ ├── wsgi.py
│
├── main/
│ ├── models.py
│ ├── views.py
│ ├── urls.py
│ ├── forms.py
│ ├── filters.py
│ ├── utils.py
│ ├── consts.py
│ ├── templates/
│ ├── static/
│ └── migrations/
│
├── users/
│ ├── models.py
│ ├── views.py
│ ├── urls.py
│ ├── forms.py
│ ├── signals.py
│ └── templates/
│
├── media/
├── static/
└── venv/
