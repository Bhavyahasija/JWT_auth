# migrate to make the changes to the model in the database

$ python3 manage.py migrate
$ python3 manage.py runserver


Once created, open your postman and make a post request to http://localhost:8000/account/api/register


Now after registration, Just login to get the JWT token. 
Now you can make request to the server with that token. To login, make a post request to http://localhost:8000/api/token/

