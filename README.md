![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Django](https://img.shields.io/badge/Django-4.x-darkgreen?logo=django)
![Database](https://img.shields.io/badge/Database-SQLite-blue)
![Status](https://img.shields.io/badge/Project-Active-success)
![License](https://img.shields.io/badge/License-MIT-yellow)

# DJClass – Django Classifieds Web Application

AutoMax is a **web-based car marketplace application** built using **Django**, designed to facilitate the **buying and selling of cars online**. The platform enables users to register, authenticate securely, and list cars for sale with detailed specifications such as brand, model, price, color, condition, and images.

The application provides an intuitive interface for buyers to browse, search, and filter available car listings, while sellers can easily manage their posted vehicles. AutoMax follows Django’s **Model–View–Template (MVT)** architecture and implements role-based functionality, media handling, and database-driven operations to deliver a scalable and user-friendly marketplace experience.

This project is developed as an **academic and portfolio project**, demonstrating full-stack web development skills, database design, authentication mechanisms, and practical use of Django for real-world applications.

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

```text
djclass/
├── manage.py
├── db.sqlite3
│
├── djclass/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── main/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   ├── filters.py
│   ├── utils.py
│   ├── consts.py
│   ├── templates/
│   ├── static/
│   └── migrations/
│
├── users/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   ├── signals.py
│   └── templates/
│
├── media/
├── static/
└── venv/

```
## 🛠 Tech Stack

- **Backend:** Python, Django
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite3
- **Authentication:** Django Authentication System
- **Version Control:** Git & GitHub


## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/djclass.git
cd djclass
```

### 2️⃣ Create and Activate Virtual Environment
```bash
python -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate      # Windows
```

### 3️⃣ Install Dependencies
```bash
pip install django
```

### 4️⃣ Apply Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5️⃣ Create Superuser
```bash
python manage.py createsuperuser
```

### 6️⃣ Run Development Server
```bash
python manage.py runserver
```

## 📸 Media & Static Files

- Uploaded images are stored in the `media/` directory
- Static assets are managed using Django static files
- Bootstrap is used for responsive UI design
  

## 🗄 Database

- Default database: **SQLite (`db.sqlite3`)**
- Database configuration can be changed in `settings.py`
- Supports PostgreSQL / MySQL for production

## 🧪 Testing
```bash
python manage.py test
```

## 🚧 Future Enhancements

- Pagination for listings
- REST API integration
- Email verification
- Advanced search & sorting
- Deployment configuration (Docker / AWS)

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a pull request

## 📜 License

This project is for educational and learning purposes.
You may add an MIT License or any other open-source license if required.

## 👤 Author

Kamalakar Buddala                                                                                                                                                                                             
B.Tech – Cybersecurity                                                                                                                                                                                        
Django & Full Stack Developer
