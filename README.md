# Blogify – Flask Blogging Platform

A full-stack blogging web application built with **Flask** for backend logic and **HTML/CSS/Bootstrap** for the frontend.  
It provides secure user authentication, post creation/editing, and a responsive UI.  
Designed with scalability in mind, it can evolve into a micro-blogging platform (like X/Threads) with future React integration.

---

## ✨ Features
- **User Accounts** – Registration, login, logout with role-based authentication.
- **Post Management** – Create, edit, delete, and view blog posts.
- **Dynamic Templates** – Jinja2 templating for server-side rendering.
- **Responsive UI** – Mobile-friendly layout using Bootstrap.
- **Extensible Architecture** – Ready for REST API endpoints and React frontend.

---

## 🛠 Tech Stack
- **Backend**: Python, Flask, Jinja2  
- **Frontend**: HTML, CSS, Bootstrap  
- **Database**: SQLite (easily swappable to PostgreSQL/MySQL)  
- **Auth**: Flask-Login / Flask-WTF  

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9+  
- pip / virtualenv

### Installation
```bash
git clone https://github.com/<your-username>/blogify-flask.git
cd blogify-flask
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
flask run
