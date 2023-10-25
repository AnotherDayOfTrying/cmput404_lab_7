# CMPUT 404 LAB 7
##  Question 0: What is the URL of your python flask_restful code on github???

https://github.com/AnotherDayOfTrying/cmput404_lab_7

## Question 1: How are Flask and Django different? What does Django provide for you that Flask does not?

Flask is a lighter framework that does not come with all the bells and whistles that django has. Django provides an ORM for a database. Authentication. Models.

## Question 2: What does REST stand for? When I say something is RESTful, what does that mean?

REST stands for Representational State Transfer. When something is RESTful it means that it can transfer the current state of a thing.

## Question 3: What does CRUD stand for? For each letter in CRUD, give the associated HTTP method.

CRUD stands for Create, Read, Update, Delete. It the basic methods that can be done upon an object.

CREATE: POST
READ: GET
UPDATE: PUT
DELETE: DELETE

## Question 4: What do HTTP 1XX Status Codes mean? HTTP 2xx? HTTP 3xx? HTTP 4xx? HTTP 5xx?

1XX status code: Here's some information!

2XX state codes: Everything is good!

3XX state codes: Redirection!

4XX state codes: Client did something wrong!

5XX state codes: Server did something wrong!

## Question 5: What is an XSS attack? Provide one way a site can be vulnerable to an XSS attack.

XSS is a "cross site scripting" attack. This is when arbitrary code can be executed on another machine w/o permission. One way a site can be vulnerable is by not sanitizing input. One would put code in an input that could be executed when loading onto another client.

## Question 6: What does CORS stand for? What situation in web application development will you need to implement CORS protection?

CORS stands for Cross Origin Resource Sharing. You will need to implement it if you have different origins that want to use the same resources. (i.e. we want to use an image from a different origin; we need to allow it using CORS) 

Hint: What does the CO part of CORS mean?
Optional: Deploy your Flask application to Heroku.

How does your Procfile change when compared to a Django application?

Would probably use `web: python3 hello.py` in the Procfile
