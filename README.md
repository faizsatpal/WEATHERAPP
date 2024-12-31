Creating the Virtual Environment
python -m venv project

Installing all the Necessary Dependencies
pip install django requests
I used Django for the backend functionality and requests for sending requests to the OpenWeatherMap API.

Creating the Main Project and the App
Now that we are done with the installations, let's create the project:
django-admin startproject weatherapplication
 cd weatherapplication
After you cd into weatherapplication project, create the application:
 python manage.py startapp weatherupdates

 Having installed Django, it is time we run it locally:
 python manage.py runserver

 
