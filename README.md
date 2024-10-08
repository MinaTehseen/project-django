# Project Setup Instructions

## Prerequisites
Before setting up the project, ensure you have the following installed on your system:
- python (version 3.x)
- pip

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

 Run the following command to install the required dependencies:
 ```
 pip install -r requirements.txt
```

##  Run the Django Development Server

Start the Django development server by running:
```
python manage.py runserver
```
The server will be available at: http://127.0.0.1:8000/