# Django Polls App

A web-based polling application built as a learning project to understand the fundamentals of the Django web framework, following the official Django documentation tutorial.

## Features

* **Admin Interface**: Manage questions and choices using Django's automatically generated admin site.
* **Public Polls**: View a list of recent polls and click through to vote.
* **Real-time Results**: See updated voting tallies immediately after casting a vote.
* **Form Safety**: Includes data validation to handle errors if a user submits a vote without selecting a choice.

## Tech Stack

* **Framework**: Django (Python)
* **Database**: SQLite (Handled automatically via Django ORM)
* **Frontend**: HTML5, standard Django templates

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd django-polls-app
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Django:**
   ```bash
   pip install django
   ```

4. **Run migrations (Creates the database tables):**
   ```bash
   python manage.py migrate
   ```

5. **Create an admin user:**
   ```bash
   python manage.py createsuperuser
   ```

6. **Start the local server:**
   ```bash
   python manage.py runserver
   ```

Open `http://127.0.0` to see the app, or `http://127.0.0` to log in with your admin user.

## Core Concepts Learned

* **Django ORM**: Interacting with a database using Python instead of writing raw SQL.
* **MVT Architecture**: Structuring code using Models, Views, and Templates.
* **Generic Views**: Reducing repetitive code by using Django's built-in `ListView` and `DetailView`.
* **Automated Testing**: Writing basic tests to check for bugs, like ensuring old questions don't display future publication dates.


## Last Updated

<!-- TIMESTAMP_START -->
_Last updated: 2026-09-01 07:51 UTC_
<!-- TIMESTAMP_END -->
