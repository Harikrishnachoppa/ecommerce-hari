# 🛒 E-Commerce Website (Django Based)

### 🚀 Developed & Maintained by [Choppa Harikrishna](https://github.com/Harikrishnachoppa)

This project is a fully functional Django-based E-Commerce Website. It allows users to browse products, add them to a cart, and simulate the checkout experience. Designed with scalability in mind, this project serves as a strong foundation for both academic and professional purposes.

---

## 📦 Features

- 🛍️ Product browsing and detail view  
- 🛒 Shopping cart functionality  
- 🧾 Order placement simulation  
- 🧑‍💼 Admin panel for product management  
- 📄 Dynamic templates using Django Templating Language  
- 🔐 User authentication system (login/register/logout)

---

## ⚙️ Tech Stack

| Area         | Technologies Used                       |
|--------------|------------------------------------------|
| Language     | Python                                   |
| Framework    | Django (Backend + Templating)            |
| Frontend     | HTML, CSS, Bootstrap                     |
| Database     | SQLite (can be switched to MySQL/PostgreSQL) |
| Version Ctrl | Git & GitHub                             |

---

## 🚀 Getting Started

### ✅ Prerequisites
- Python 3.10 or above
- Git

### 📥 Installation

```bash
# Clone the repo
git clone https://github.com/Harikrishnachoppa/ecommerce-hari.git
cd ecommerce-hari

# Create virtual environment
python -m venv env
env\Scripts\activate   # On Windows

# Install dependencies
pip install -r requirements.txt

# Migrate the database
python manage.py makemigrations
python manage.py migrate

# Run the development server
python manage.py runserver
