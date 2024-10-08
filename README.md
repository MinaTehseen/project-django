# Django Project Management System

This is a Django-based Project Management System that provides user authentication using JWT and allows CRUD operations on projects and tasks.

## Project Setup Instructions

## Prerequisites
Before setting up the project, ensure you have the following installed on your system:
- Python 3.8+
- pip (Python package installer)

## Create a Virtual Environment
Create a virtual environment to isolate the project dependencies. Run the following command in the root folder of the project:

For macOS/Linux:
```
python3 -m venv venv
```

For Windows:
```
python -m venv venv
```
This will create a `venv` folder with a virtual environment.

##  Activate the Virtual Environment

Once the virtual environment is created, activate it:

On macOS/Linux:
```
source venv/bin/activate
```

On Windows:
```
venv\Scripts\activate
```

##  Install Dependencies

After activating the virtual environment, install the required dependencies using pip:
 ```
 pip install -r requirements.txt
```

##  Run the Django Development Server

Start the Django development server by running:
```
python manage.py runserver
```
The server will be available at: http://127.0.0.1:8000/

## After Adding New Models
If you create a new model or make changes to existing models, you will need to run makemigrations and migrate to apply those changes to the database.

```
python manage.py makemigrations
```

```
python manage.py migrate
```