# Sohaib-Portfolio-Website
This repository contains the source code for a personal portfolio website built using Django. This project showcases a personal portfolio, including features and projects in a structured and professional manner.


## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.x
- `pip` (Python package installer)

## Setup Instructions

1. **Clone the Repository:**

   ```bash
   git clone git@github.com:sohaibssb/Sohaib-Portfolio-Website.git
   cd Sohaib-Portfolio-Website

2. **Create and Activate a Virtual Environment:**
    ```bash
    python3 -m venv venvPort
    source venvPort/bin/activate

3. **Install Required Packages:**
    ```bash
    pip install django Pillow django-ckeditor

4. **Start a New Django Project:**
    ```bash
    django-admin startproject sohaib_portfolio

5. **Create a New Django App:**
    ```bash
    python manage.py startapp main

6. **Freeze the Installed Packages into requirements.txt:**
    ```bash
    pip freeze > requirements.txt

7. **Apply Migrations:**
    ```bash
    python manage.py makemigrations
    python manage.py migrate

8. **Create a Superuser for Admin Access:**
    ```bash
    python manage.py createsuperuser

9. **Run the Development Server:**
    ```bash
    python manage.py runserver

## Running the Project

Once the development server is running, you can access the portfolio website at http://127.0.0.1:8000/. To access the Django admin interface, navigate to http://127.0.0.1:8000/admin/ and log in with the superuser credentials you created.