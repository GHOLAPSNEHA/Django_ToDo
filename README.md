# Django_ToDo

A simple and user-friendly To-Do List Web Application built using Django.
This application allows users to create, manage, update, and delete tasks easily.
It is a beginner-friendly project demonstrating Django CRUD operations, MVT architecture, and database integration.

## feature

-Add new tasks

-Update existing tasks

-Mark tasks as completed

-Delete tasks

-View all tasks in a list

-Simple and responsive interface

## Tech Stack

| Technology           | Purpose             |
| -------------------- | ------------------- |
| **Python**           | Backend programming |
| **Django**           | Web framework       |
| **HTML5**            | Structure of pages  |
| **CSS3 / Bootstrap** | Styling             |
| **SQLite**           | Database            |
| **Git & GitHub**     | Version control     |


## Screenshots

![App Screenshot](https://dummyimage.com/468x300?text=App+Screenshot+Here)



![Todo App](/repository/assets/employee.png?raw=true "Employee Data title")

## Run Locally

Clone the project

```bash
  git clone git clone https://github.com/GHOLAPSNEHA/Django_ToDo.git
```

Go to the project directory

```bash
  cd ToDo
```

Create Virtual Environment

```bash
  python -m venv venv
```

Activate the environment


windows
```bash
  venv\Scripts\activate
```
Mac/Linux
```bash
source venv/bin/activate
```

Install Dependencies
```bash
pip install -r requirements.txt
```
Apply Migrations
```bash
python manage.py migrate
```
Run the Server
```bash
python manage.py runserver
```
Open browser and visit:
```bash
http://127.0.0.1:8000/
```

## What You Will Learn

✔ Django project setup

✔ Models, Views, Templates (MVT)

✔ CRUD operations

✔ Django admin panel

✔ URL routing

✔ Database migrations

## Future Improvements

🔹 User authentication (Login/Signup)

🔹 Task categories

🔹 Due dates & reminders

🔹 REST API with Django REST Framework

🔹 Deployment on Heroku / Render