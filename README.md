# Integrating MongoDB ATLAS with Django 3.1.1

![Final GUI OUTPUT](https://github.com/tinshade/djatlas/main/SS/MyCluster.png "Here is my ATLAS cluster after the migration!")

## Pre-Requisites
	1. Must have a Mongo ATLAS account.
		> Create one here[https://www.mongodb.com/try]. It's free to learn!
	2. Python 3.6 or above
	3. Basics of Mongo ATLAS ( Cluster and DB creation )

---

## Installation and Setup
	1. Creating a virtual environment
		```python -m venv venv```

	2. Activating the virtual environment:
		```venv\Scripts\activate```

	3. Installing dependencies:
		```pip install -r requirements.txt```

	4. Repalce your connection string in HOSTS variable the 'mongo-client.py' file.
		> The default is set to localhost, adding a URI will use the cloud DB instead.

	5. Starting Django project:
		```django-admin startproject proj_name .```
		> Creates new project in the current folder

	6. Replace credentials in the Databases section of your proj_name/settings.py file!
		> You will need to create a new admin user and use those credentials if you haven't already!

	7. Test by applying initial migrations:
		```python manage.py migrate```

---

## Screenshots
![Final GUI OUTPUT](https://github.com/tinshade/djatlas/main/SS/MyCluster.png "Here is my atlas cluster after the migration!")

![Final CMD OUTPUT](https://github.com/tinshade/djatlas/main/SS/output.png "Here is what your output should look like")

![Where to find connection string](https://github.com/tinshade/djatlas/main/SS/urlstring.png "Your URL String appears when you hit Connect > Connect to application > Python3.6 or above from the cluster.")