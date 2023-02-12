# Whatsapp-Clone-Using-Django


# Basic Principle/Architechture
This project is basically a real time chat application like whatsapp which supports 
one-one messaging with less latency. In this project Django-channels has been used to 
maintain the connection status stable through the ASGI server and to get real time 
live chat notification we have used Websocket which creates the connection. To get 
less latency we have used redis server.


Tool Used: Python, Django, Django-Channels, Websocket, Redis Server, SQLITE3, Rest API, HTML, CSS, 
Javascript etc.


--> Here 'chat' is the project folder & 'core' is the project app


Step-1: Installing the redis-server for windows
https://github.com/microsoftarchive/redis/releases


# Step-2: Creating Virtual Environment
Use the command: python -m venv "env-name you want to set"
Example: python -m venv myenv


# Step-3: Changing directory
Use the command: cd "project directory name"
Example: cd django-whatsapp-main


# Step-4: Installing requirements.txt
Use this command: pip install -r requirements.txt


# Step-5: Migrate all the changes into the database
Use this command: python manage.py migrate


# Step-6: Creating super user to acces the django-admin panel
Use this command: python manage.py createsuperuser


# Step-7: Run the ASGI server
Use the command: python manage.py runserver

--> Please check the server which is running in console is ASGI/CHANNEL or not

--> Please use the same versions which is listed in requirements.txt to get ASGI server

--> The project will not be executed if the server is Development server

--> Go to any browser and search for: http://localhost:8000
