Event Registration API
Overview

A Django REST API for managing events and registrations. Users can register for events and track their registration status.

Features

CRUD operations for Users, Events, and Registrations

Registration status: pending, confirmed, cancelled

Database integration: MySQL or SQLite

API testable via Postman or Django REST Framework browser

Setup Instructions

Clone the repository

git clone <your-github-repo-link>
cd event_api


Install dependencies

pip install -r requirements.txt


Apply migrations

python manage.py makemigrations
python manage.py migrate


Run the server

python manage.py runserver


Access API
Open http://127.0.0.1:8000/api/
 to explore endpoints.

Demo Data

You can test the API using the provided Postman collection (EventAPI.postman_collection.json). The collection includes sample data for:

Users

Events

Registrations

Optional Notes

If using MySQL, ensure the database is created (e.g., eventdb) and credentials are updated in settings.py or .env.

Use Django admin to quickly view and manage data: http://127.0.0.1:8000/admin/