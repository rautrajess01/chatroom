# chatroom
A simple Django-based chatroom web app where users can create, join, and discuss in different rooms and topics.

# 💬 Django Chatroom App

This is a Django-based web application that allows users to create and join chat rooms, interact with others, and manage topics. It’s a simple real-time communication platform built with core Django features.

## 🚀 Features

- User registration and login system
- Create, update, delete chat rooms
- Join and participate in different discussion topics
- Real-time-like messaging experience
- Admin panel to manage content

## 🛠 Tech Stack

- **Backend**: Django (Python)
- **Database**: SQLite3 (default for development)
- **Frontend**: HTML/CSS (default Django templates)

## 📂 Project Structure

```
chatroom/
├── base/               # Main app with models, views, forms
├── chatroom/           # Project settings and URLs
├── db.sqlite3          # SQLite database
├── manage.py           # Django entry point
├── apitest.html        # Sample HTML test (optional)```

## ⚙️ Installation & Setup

### 1. Clone the repository


git clone https://github.com/your-username/chatroom.git
cd chatroom
```

### 2. Create and activate a virtual environment


python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate
```

### 3. Install dependencies
pip install -r requirements.txt
```

> ⚠️ If `requirements.txt` is missing, install manually:
`
pip install django
```

### 4. Run migrations


python manage.py migrate
```

### 5. Start the development server


python manage.py runserver
```

Now visit [http://127.0.0.1:8000](http://127.0.0.1:8000) to use the app.

## 👤 Admin Access

Create a superuser to access the admin panel:

```bash
python manage.py createsuperuser
```

Then log in at [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)

## 📌 Notes

- Designed for educational or small-scale community use.
- You can customize topics, room styles, and user interaction rules as needed.
