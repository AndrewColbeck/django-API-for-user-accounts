# Simple REST API Demo made with Django
User administration back-end made with the Django Rest Framework which allows for dev administration of a simple user account system (not for production purposes)

## Launch Development Server
### Activate virtual environment
`source env/bin/activate`

### Install Required Packages from included requirements.txt file
`pip install -r requirements.txt`

### Create a superuser env variable to access GUI, or post new users from cli with
`python manage.py createsuperuser --email something@somewhere.com --username admin`

### Deploy Development Server locally
`python manage.py runserver`
server address: `http://127.0.0.1:8000/`

### Wrap Up
- Quit Server `Ctrl+C`
- Deactivate virtual environment: `deactivate`

### Screenshot
![Screenshot of GUI with user accounts](https://gdurl.com/uiXc6)


#### Tutorial link:
https://www.django-rest-framework.org/tutorial/quickstart/
