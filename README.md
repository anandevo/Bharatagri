# Bharatagri
Bharatagri coding test


Tried creating a Django project where a new joinee can get his/her email id by using API.

Within Django created an api which contains the model for firstname, secondname, email id and employee id
firstname, secondname and emp id are manually filled but email id is generated from data.

The API app contains the following python files -
         Views.py - Contains data to be displayed
         Serializers.py - Contains properties to convert data into json format
         Tasks.py - Contains code to display data on to the web page
         
 The main project app contains
     celery.py - Contains code to run and generate data for the email id
     
     
 Redis server and Sqlite as a database has been used.    
