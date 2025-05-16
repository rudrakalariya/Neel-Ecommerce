# 🛒 Neel-Ecommerce

**Neel-Ecommerce** is a Django-based e-commerce platform with secure user authentication, product catalog, shopping cart, and order management functionalities. Built to deliver a solid backend structure for online shopping applications.

---

## 🚀 Features

### 👤 User Management
- 🔐 Secure registration and login
- 🧾 User profile handling
- 🔑 Password encryption with Django’s auth system

### 🛍️ Product Management
- 🗂️ Product categories
- 📦 Add/edit/delete products
- 📸 Product image support

### 🛒 Shopping Cart & Orders
- ➕ Add to cart
- 🧺 View/update cart
- 🧾 Place orders and track order history

---

## 🛠 Tech Stack

| Component      | Technology        |
|----------------|-------------------|
| ⚙️ Backend      | Django (Python)    |
| 💾 Database     | SQLite (default) or MySQL |
| 🎨 Frontend     | HTML, CSS, Bootstrap |
| 🧪 Dev Tools     | Django Admin Panel |
| ☕ Python        | 3.10+ recommended |

---

## 📋 Prerequisites

- Python 3.10 or higher
- pip (Python package manager)
- Virtualenv (optional but recommended)

---

## 🔧 Installation & Setup

### 1. 📥 Clone the repository

```bash
git clone https://github.com/rudrakalariya/Neel-Ecommerce.git
cd ec
```
### 2. 🧪 Create and activate a virtual environment
```bash
python -m venv env
source env/bin/activate   # On Windows use: env\Scripts\activate
```
### 3. 📦 Install dependencies
```bash
pip install -r requirements.txt
```
### 4. ⚙️ Set up the database
```bash
python manage.py makemigrations
python manage.py migrate
```
### 5. 👤 Create a superuser (admin)
```bash
python manage.py createsuperuser
```
### 6. ▶️ Run the development server
```bash
python manage.py runserver
```
🔗 Visit: http://localhost:8000

---

## 🗂️ Project Structure (Django)
```
Neel-Ecommerce/
├── ecommerce/           # Django project settings
├── app/                # Core app for products, cart, orders
├── templates/           # HTML templates
├── static/              # Static files (CSS, JS, images)
├── db.sqlite3           # Default database
└── manage.py
```
---

## 🔐 Security
🔒 Passwords encrypted with Django's built-in hashing

✅ Login required for cart and order actions

🔐 Admin panel secured with superuser access
