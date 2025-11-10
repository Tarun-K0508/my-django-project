#  Django Ecommerce Web App

This is a **Django-based full-stack web application** built for learning and demonstration purposes.  
It includes core app functionalities and a conversation module to handle user interactions dynamically.  
The project uses Django, Python, HTML, CSS, and Bootstrap for a responsive and modern interface.

---

## Features
- **User Authentication** – Register, Login, and Logout functionality  
- **Conversation System** – Send, receive, and display messages between users  
- **Core App** – Handles main website pages and models  
- **Admin Panel** – Manage users, messages, and other data easily  
- **Responsive Design** – Built with modern front-end practices

---

## Technologies Used
- **Backend:** Python, Django  
- **Frontend:** HTML5, CSS3, Bootstrap  
- **Database:** SQLite3 (default Django database)  
- **Version Control:** Git & GitHub  
- **IDE:** VS Code  

---

## Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Tarun-0508/my-django-project.git
cd my-django-project

python -m venv env

env\Scripts\activate

source env/bin/activate

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver

Go to 👉 http://127.0.0.1:8000/ to view the app.
