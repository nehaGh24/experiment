# Django Blog Website

This is a basic blog website built with Django. It allows users to write, edit, delete, and read blog posts. Users can also leave comments and sign up to create their own posts.

## Features

- User accounts (sign up, login, logout)
- Create, edit, and delete blog posts
- Comment on blog posts
- Easy-to-use and mobile-friendly design

## What You Need

Make sure you have these installed:

- Python 3.8 or higher
- Django 4.0 or higher
- pip (to install Python packages)
- Git (for version control)

## How to Install

1. *Clone this project*:
   bash
   git clone https://github.com/yourusername/django-blog.git
   cd django-blog
   

2. *Set up a virtual environment*:
   bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   

3. *Install the required packages*:
   bash
   pip install -r requirements.txt
   

4. *Set up the database*:
   bash
   python manage.py migrate
   

5. *Create an admin user* (to manage the blog):
   bash
   python manage.py createsuperuser
   

6. *Start the development server*:
   bash
   python manage.py runserver
   

7. *Open the website*:  
   Go to http://127.0.0.1:8000/ in your browser. You can log in to the admin page at http://127.0.0.1:8000/admin/.

## Deploying to the Web

To put the website online:

1. Change DEBUG = False in settings.py.
2. Set ALLOWED_HOSTS to your domain name.
3. Use a database like PostgreSQL for production.
4. Set up a production server (e.g., Gunicorn or uWSGI).
5. Serve static files (e.g., with Amazon S3).
6. Set up SSL for HTTPS.

## Contributing

Feel free to submit pull requests or open issues if you have suggestions or improvements.
