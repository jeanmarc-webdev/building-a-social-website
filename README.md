# Django Social Website

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

## 📚 Project Structure (by chapters)

### Chapter 4 — Building a Social Website
- User authentication (login, logout, password reset/change)
- User registration system
- Custom user profile model
- Media file configuration
- Django admin user management

---

### Chapter 5 — Social Authentication
- Email-based authentication backend
- Prevent duplicate email registration
- Google OAuth integration
- HTTPS development server setup
- Authentication pipeline customization
- Auto profile creation for social users

---

### Chapter 6 — Sharing Content on Your Website
- Image bookmarking system
- Many-to-many relationships
- Custom Django forms behavior
- JavaScript bookmarklet
- AJAX-style interactions
- Image thumbnails with easy-thumbnails
- Infinite scroll pagination

---

### Chapter 7 — Tracking User Actions
- Follow / unfollow system
- Intermediate models for relationships
- Activity stream system
- Generic relations (ContentType framework)
- Query optimization (select_related / prefetch_related)
- Signals for denormalization
- Redis integration (views counting + rankings)
- Django Debug Toolbar for performance analysis

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

---

## 🚀 What I Learned

- Building scalable Django applications step-by-step
- Managing relational database models effectively
- Implementing authentication systems (standard + social)
- Using Redis for real-time data tracking
- Improving query performance with Django ORM optimization
- Integrating JavaScript with Django backend
- Structuring full-stack web applications

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
```

---

## 📌 Notes

This project is educational and follows a book-based learning path.  
All features were implemented progressively following Django best practices.

---

## 📷 Screenshots

Add your chapter screenshots in a `/screenshots` folder (optional but recommended).

---

## 🔗 Related Repository

Portfolio version:
`building-a-social-website-portfolio`

Link for Building A Social Website Portfolio

https://github.com/jeanmarc-webdev/building-a-social-website-portfolio