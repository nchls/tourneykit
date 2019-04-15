# Tourneykit

## Running locally
* Install PostgreSQL and create a database named tourneykit owned by user tourneykit with password tourneykit
* Install JS dependencies: `npm install`
* If you have multiple versions of Python installed, make sure that all the Pip and Python commands below use Python 3 specifically.
* Install Python dependencies: `pip install -r requirements.txt`
* Run migrations to create database tables: `python manage.py migrate`
* Create a Django superuser: `python manage.py createsuperuser`
* Start the Node server: `npm start`
* In a separate terminal, start the Django server: `python manage.py runserver`
* Visit http://127.0.0.1:8000/ to view the main page of the app
* Visit http://127.0.0.1:8000/admin and log in as the superuser to CRUD some content
