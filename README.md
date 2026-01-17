DJClass – Django Classifieds Web Application

DJClass is a Django-based classifieds web application that allows users to register, log in, and post classified listings with details such as category, brand, color, description, images, and more. The project follows Django’s standard MVT (Model–View–Template) architecture and uses SQLite as the default database.

🚀 Features

User authentication (registration, login, logout)

User profile management

Create, update, and delete classified listings

Listing categories, brands, colors, and descriptions

Image upload and media handling

Like / favorite listings

Filtering and searching of listings

Django admin panel for management

Bootstrap-based responsive UI

djclass/
│
├── manage.py
├── db.sqlite3
│
├── djclass/                # Project configuration
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   ├── wsgi.py
│
├── main/                   # Core classifieds app
│   ├── models.py           # Listing, category, likes models
│   ├── views.py            # Business logic
│   ├── urls.py             # App routing
│   ├── forms.py            # Django forms
│   ├── filters.py          # Listing filters
│   ├── utils.py            # Helper utilities
│   ├── consts.py            # Constants
│   ├── templates/          # HTML templates
│   ├── static/             # CSS, JS, images
│   └── migrations/
│
├── users/                  # User management app
│   ├── models.py           # Custom user / profile models
│   ├── views.py            # Auth & profile views
│   ├── forms.py            # User forms
│   ├── signals.py          # Django signals
│   ├── urls.py             # User routing
│   └── templates/
│
├── media/                  # Uploaded images
├── static/                 # Global static files
└── venv/                   # Virtual environment (should be ignored)
