# todo_task_app  https://to-do-task-app-cyan.vercel.app/auth/register
 🚀 Flask To-Do Task Manager  A sleek, lightweight, and fully functional web application built using Python and Flask to manage daily tasks efficiently. This project features user authentication, a structured database layout, and full CRUD (Create, Read, Update, Delete) capabilities. 

 Features: 
 
 •	User Authentication: Secure login and session management to keep user tasks private.
 •	Task Management (CRUD): Easily add new tasks with specific titles.
 •	Dynamic Status Toggling: Cycle through task states seamlessly with a single click (Pending ➔ Working ➔ Done). 
 •	Task Cleanup: Quick task deletion with built-in JavaScript confirmation alerts. 
 •	Clean & Responsive UI: Styled elegantly using modern HTML5 and customized CSS grid/flexbox layouts.
 •	Robust Database: Built using SQLAlchemy ORM with an SQLite backend for persistent data storage.
 
   
   🛠️ Tech Stack  
   •	Backend: Python 🐍, Flask Framework 
   •	Database: SQLite, Flask-SQlAlchemy (ORM) 
   •	Frontend: HTML5, CSS3, Jinja2 Template Engine   
   📂 Project Structure

To-Do task app/
│
├── app/
│   ├── routes/
│   │   ├── auth.py          # Authentication routing (Login/Logout)
│   │   └── task.py          # Task management logic (Add, Toggle, Clear)
│   ├── templates/
│   │   ├── base.html        # Main layout structure
│   │   └── task.html        # Main dashboard and task view
│   ├── models.py            # Database schemas (User & Task models)
│   └── __init__.py          # App initialization & DB config
│
├── venv/                    # Virtual Environment
└── run.py                   # App entry point
