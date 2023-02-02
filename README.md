# AdminUI

This project is an API built with Django/Django REST Framework. It provides endpoints for an admin user to view and edit users and groups.

## Clone the Repository

```
git clone https://github.com/becathey/admin-ui-django.git
```

## Create & Activate a Virtual Environment

In the project directory, create and activate a virtual environment. For example:

```
python3 -m venv .venv
source .venv/bin/activate
```

## Install the Dependencies

To install the dependencies, run:

```
pip install -r requirements.txt
```

## Environment Variables

Create a .env file in root of project, and add a SECRET_KEY:

```
SECRET_KEY='<create-and-add-your-secret-key-here>'
```

The .env file should be added to a .gitignore file.

## Run the App

To run the app in development mode, run:

```
python manage.py runserver
```

Open [http://localhost:8000](http://localhost:8000) in the browser to view the application.