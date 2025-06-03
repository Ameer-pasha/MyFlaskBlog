# Flask Blog App 📝

A fully functional blogging web application built using Flask. This app includes features like user authentication, post creation/editing, commenting, and admin-only access for managing blog content. It also includes Gravatar integration and rich-text support via CKEditor.

---

## 🚀 Features

- User Registration & Login (Flask-Login)
- Admin-only control to:
  - Add, edit, delete blog posts
- Comment system for logged-in users
- Rich-text post editing (CKEditor)
- Profile pictures with Gravatar
- Responsive layout with Bootstrap5
- SQLAlchemy with SQLite database

---

## 🧰 Tech Stack

- **Backend:** Python, Flask, Flask-SQLAlchemy
- **Frontend:** HTML5, Bootstrap5, Jinja2
- **Authentication:** Flask-Login
- **Text Editor:** Flask-CKEditor
- **Profile Avatars:** Flask-Gravatar
- **Password Security:** Werkzeug hash (pbkdf2:sha256)

---

## 📁 Project Structure

│
├── static/ # Static files like CSS, JavaScript, images
├── templates/ # HTML template files for Flask
├── forms.py # WTForms for handling forms
├── main.py # Main Flask application file
├── requirements.txt # Project dependencies
├── Procfile # For deployment configurations (e.g., Heroku)
└── .gitignore # Git ignore rules


---

## Installation

Instructions to install dependencies:

```bash
pip install -r requirements.txt


## Usage
python main.py
