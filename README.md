## API (CRUD) on DRF (with auth) :airplane:
This is a quick set-up of **CRUD** - Create, Read, Update, and Delete on the Django Rest Framework.

The authentication is implemented using JWT Auth for **DRF** - Django Rest Framework


Feel free to utilize this repo for API studies, or a quick template for projects or application development.
 

#### API Endpoints

 Endpoint | Functionality
--- | ---
`/api/user/create` | Create user
`/api/user/profile/{pk}` | Fetch user
`/api/user` | Fetch users
`/api-token-auth` | Fetch auth token
`/api/user/update/{pk}` | Change user
`/api/user/destroy/{pk}` | Delete user


## Installation 

Boot virtual env:

    pip install virtualenv
Clone this repo

    git clone https://github.com/p8ul/django-rest-framework-boilerplate
Create a virtual environment

    cd cd API-crud-drf
    virtualenv .venv
    source .venv/bin/activate
Install dependancy packages

    pip install -r requirements.txt
Make migrations & migrate

    python manage.py makemigrations
    python manage.py migrate
Create user
    
    python manage.py createsuperuser

## Launching the app
    python manage.py runserver

## Initiate Tests
    python manage.py test
