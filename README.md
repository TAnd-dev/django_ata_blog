# Django Blog
This project is a simple blog application built with Django. It allows users to view, search, and share blog posts. Users can also leave comments on individual posts. The project uses the django-taggit library for tagging posts and provides search functionality using PostgreSQL's full-text search features.

## Features
- Post List: View all published blog posts with pagination support.
- Post Detail: View detailed information for a specific post, including comments and similar posts.
- Post Share: Share a blog post via email.
- Post Comment: Leave comments on blog posts.
- Post Search: Search for blog posts by title using Trigram similarity.

## Setup and Installation
- Clone the repository:

`git clone https://github.com/yourusername/django-blog.git`

`cd django-blog`

- Install the required dependencies:
`pip install -r requirements.txt`

## Apply the migrations:
`python manage.py migrate`

## Create a superuser to access the Django admin:
`python manage.py createsuperuser`

## Run the development server:
`python manage.py runserver`

Access the blog at http://127.0.0.1:8000/
