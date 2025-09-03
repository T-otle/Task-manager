# Team Task Management Web App

A web-based **Task Management System** built using **Flask**, **SQLite**, and **Flask-Login**, allowing users to create, assign, and manage tasks with role-based access control. This project demonstrates full-stack development, authentication, CRUD operations, and deployment.

---

## 🌟 Features

- User registration and login with hashed passwords.
- Role-based access:
  - **Admin**: View and manage all tasks.
  - **Member**: View personal tasks and tasks shared with them.
- Task CRUD operations:
  - Create, edit, delete tasks.
  - Assign tasks to other users.
- Dashboard to view personal and shared tasks.
- Flash messages for success/error notifications.
- User-friendly forms and templates.

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask, Flask-Login, Flask-SQLAlchemy
- **Database:** SQLite
- **Frontend:** HTML, CSS, Bootstrap (optional)
- **Tools:** Git, VSCode, Postman (optional)

---

## ⚡ Setup Instructions

1. **Clone the repository**
```bash
git clone <your-github-repo-link>
cd <repo-folder>
Create virtual environment and install dependencies

bash
Copy code
python -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate      # Windows
pip install -r requirements.txt
Run the application

bash
Copy code
python app.py
Open your browser and navigate to http://127.0.0.1:5000

🧪 Running Unit Tests
Install pytest if not already installed:

bash
Copy code
pip install pytest pytest-flask
Run tests:

bash
Copy code
pytest -v

