## API (CRUD) on DRF (with auth)
This is a quick set-up of **CRUD** - Create, Read, Update, and Delete on the Django Rest Framework.

The authentication is implemented using JWT Auth for **DRF** - Django Rest Framework


Feel free to utilize this repo for API studies, or a quick template for projects or application development.
 
#### Jwt token endpoint
Method | Endpoint | Functionanlity
--- | --- | ---
POST | `/api-token-auth` | Request jwt token

#### API Endpoints

Method | Endpoint | Functionality
--- | --- | ---
GET | `/api/user/create` | Creates a user
GET | `/api/user/profile/{pk}` | Retrieve a user
POST | `/api/user` | List users
PUT | `/api/user/update/{pk}` | Edit a user
DELETE | `/api/user/destroy/{pk}` | Delete a user


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
