# Python_task4
Flask User API

This is a simple Flask-based REST API that uses SQLAlchemy for ORM and Marshmallow for serialization. It manages basic user data (name and contact) and stores it in an SQLite database.

## 🔧 Features

📦 Add users (name + contact)

📡 REST API-ready setup

💾 SQLite-based persistent storage

📐 Marshmallow for schema serialization


## 🧰 Requirements

Make sure you have Python installed (3.7+ recommended).

Install dependencies:

pip install flask flask_sqlalchemy flask_marshmallow

🚀 How to Run

python main.py

It will start the server at:

http://127.0.0.1:3456/

## 📂 Project Structure

├── main.py         # Main application file
├── db.sqlite       # Database file (auto-created on run)
└── README.md       # Project documentation

## 🏗️ API Structure

> Note: You need to add routes to create, read, update, or delete users. The current code defines the schema and app only.



To Add (example ideas):

POST /user – Create a user

GET /users – List all users

GET /user/<id> – Get single user

PUT /user/<id> – Update user

DELETE /user/<id> – Delete user


## 📘 Example User Schema
```
{
  "id": 1,
  "name": "Hari",
  "contact": "9876543210"
}
```
