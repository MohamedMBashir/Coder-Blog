# Coder Blog

Coder Blog is a dynamic, user-friendly blog application that I designed specifically for coding enthusiasts. It provides a platform where users can share and learn from various coding lessons and tutorials.

The application is built with Flask, a lightweight and powerful web framework for Python. I used SQLite for the backend database to store user, blog post, and comment data. For the frontend, I used Flask-Bootstrap to apply Bootstrap styles, Flask-CKEditor for the rich text editor, and Jinja2 for rendering the HTML pages.

## Features

- User registration and authentication
- Creation, editing, and deletion of blog posts
- Commenting on blog posts
- Admin functionality for managing posts
- Gravatar support for unique user avatars

## Setup and Installation

1. Clone the repository
2. Install the dependencies using `pip install -r requirements.txt`
3. Set up the database by running `python main.py db init`, `python main.py db migrate`, `python main.py db upgrade`
4. Run the application using `python main.py runserver`