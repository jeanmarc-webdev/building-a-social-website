# Django Social Website Codes

This project was built while following *Django 5 By Example* by Antonio Melé.

It is a social web application developed progressively through multiple chapters, implementing authentication, social features, content sharing, and real-time tracking systems using Django.

---

## 📌 Project Overview

This project demonstrates the development of a complete social platform using Django, including:

- User authentication system
- Social authentication (Google login)
- User profiles and follow system
- Image sharing and bookmarking
- Activity stream (user actions)
- Redis-based tracking and ranking system
- JavaScript interactions with Django backend

---

## 🏗️ Tech Stack

- Python
- Django
- Django Authentication System
- Django ContentTypes Framework
- JavaScript (Vanilla)
- SQLite / PostgreSQL
- Redis
- HTML / CSS
- Django Debug Toolbar
- easy-thumbnails
- Python Social Auth
- Django Extensions

---

## ⚙️ Key Features

- User registration and authentication system
- Social login (Google OAuth)
- Follow/unfollow users
- Image upload and bookmarking system
- Activity stream (likes, follows, bookmarks)
- Infinite scroll pagination
- Redis-powered analytics (views & ranking system)
- JavaScript-enhanced interactions
- Performance optimization tools

This project also includes a portfolio version that documents the development process and learning progression across chapters:
- 👉 https://github.com/jeanmarc-webdev/building-a-social-website-portfolio


---

## 📦 Setup (basic)

```bash
git clone https://github.com/jeanmarc-webdev/building-a-social-website.git
cd building-a-social-website

python -m venv env
source env/bin/activate  # or .\env\Scripts\activate on Windows

pip install -r requirements.txt

python manage.py migrate
python manage.py runserver

👉 https://github.com/jeanmarc-webdev/building-a-social-website-portfolio


## 🔗 Related Repository

This project also includes a portfolio version that documents the development process and learning progression across chapters:

👉 https://github.com/jeanmarc-webdev/building-a-social-website-portfolio
