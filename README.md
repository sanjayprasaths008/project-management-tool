# Project Management Tool

A collaborative project management web application developed as part of my Full Stack Development Internship at CodeAlpha.

The application helps teams create projects, manage tasks, assign tasks to users, and communicate through task comments.

## Features

- User registration and login
- User authentication
- Create and manage group projects
- Create and manage tasks
- Assign tasks to team members
- Task status management
- Task cards
- Comments and communication within tasks
- Project and task management
- Database for users, projects, tasks, and comments
- Real-time updates using WebSockets
- Notifications for task updates

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Django (Python)
- SQLite
- WebSockets

## Project Structure

project-management-tool/
│
├── manage.py
├── requirements.txt
├── README.md
│
├── projectmanager/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── users/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── admin.py
│
├── projects/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── admin.py
│
├── tasks/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── admin.py
│
├── templates/
│   ├── home.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── project.html
│   ├── task.html
│   └── profile.html
│
└── static/
    ├── css/
    ├── js/
    └── images/
