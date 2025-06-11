# 📘 Learning Log Project

**Learning Log** is a Django-based web application that allows users to track topics they’re learning and make journal-style entries.  
It offers a full-stack solution, including user authentication, topic management, and entry tracking — ideal for practicing web development and data management.

> ⚠️ **Note:** Due to issues uploading some Django and pip files, the app may not run out-of-the-box after cloning.  
> Feel free to contact me if you'd like support getting it running.

---

## 🧠 Project Overview

- Create and manage topics you're learning about.
- Add journal entries for each topic.
- Register, log in, and manage your own data securely.
- Built with Django (backend), HTML/CSS (frontend), and Bootstrap for responsiveness.

---

## 🔍 Skills Demonstrated

- **Django Web Development**: Views, models, templates, forms, and user auth.
- **Data Management**: Clean CRUD operations via Django ORM.
- **User Interaction**: Input forms, session handling, and dynamic rendering.
- **Database Integration**: Structured model relationships and queries.

---

## ✨ Key Features

- 🔐 **User Authentication**: Secure registration, login, logout system.
- 📂 **Topic Management**: Create, view, edit, and delete learning topics.
- 📝 **Entry Tracking**: Add journal-style entries under each topic.
- 💻 **Responsive UI**: Clean interface built with `django-bootstrap5`.

---

## 🧪 Future Improvements

- 📊 **Data Visualization**: Add learning stats and progress charts (using Plotly/Matplotlib).
- 🔔 **User Notifications**: Reminders to update entries regularly.
- 🛡️ **Security Enhancements**: Add 2FA and stronger password requirements.

---

## ⚙️ How to Run the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/learning-log.git
cd learning-log
````

### 2. Set Up Virtual Environment

```bash
python -m venv ll_env
source ll_env/bin/activate  # Windows: ll_env\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Development Server

```bash
python manage.py runserver
```

Visit the app at [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 🗂️ Project Structure

```
learning-log/
├── learning_logs/         # Main app: models, views, templates
├── users/                 # User authentication
├── templates/             # HTML templates
├── static/                # Static assets (CSS, JS)
├── db.sqlite3             # SQLite database
├── manage.py              # Django entry point
└── requirements.txt       # Python dependencies
```

---

## 📌 Notes

* Built with **Python 3.x** and **Django**
* Designed for learning full-stack development fundamentals
* A great foundation for building personal or educational journaling apps

---

Feel free to fork, star ⭐, or contribute!
