# django-cheats
## Django Cheatsheet


### Create and navigate to the project directory

```
$ mkdir <directory-name> && cd <directory-name>
```
	

    
### Create a python virtual environment
```
$ python3 -m venv .env
```
	

    
### Activate the virtual environment
```
$ source .env/bin/activate
```
	

    
### Install django and psycopg2-binary
```
$ pip3 install django psycopg2 psycopg2-binary
```
	

    
### Create a requirements file
```
$ pip3 freeze > requirements.txt
```


	
### Create the django project
```
$ django-admin startproject <project-name> .
```
	

	
### Create the first app
```
$ python3 manage.py startapp <app-name>
```
	

	
### Run the Server
```
$ python3 manage.py runserver
```



### The migrate command is used to update the database schema
```
$ python3 manage.py migrate
```



### Create migration files for all Models that have been added or changed since the last migration
```
$ python3 manage.py makemigrations
```



### A super user is an administrator for the site. When you are logged in to this account, you can access the Admin app to add additional users and manipulate Model data.
```
$ python3 manage.py createsuperuser
```



### Change your password
```
python3 manage.py changepassword <user_name>
```
	
