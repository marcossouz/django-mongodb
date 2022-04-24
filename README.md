# MongoDB + Django Rest Framework CRUD Rest API example

In this tutorial, we’re gonna create Python 3/Django & MongoDB CRUD example with Django Rest Framework for building Rest Apis. You’ll know:

- How to setup Django to connect with MongoDB Database
- How to define Data Models and migrate it to MongoDB
- Way to use Django Rest Framework to process HTTP requests
- Way to make Django CRUD Operations with MongoDB Database

## Technology
- Python 3.7
- Django 2.1.15
- Django Rest Framework 3.11.0
- djongo 1.3.1
- django-cors-headers 3.2.1
- MongoDB 3.4 or higher

## How to run
- `python3 -m venv venv`
- `source venv/bin/activate`
- `pip install -r requirements.txt`
- `python manage.py runserver 8080`

# Vue.js 2 CRUD Application with Vue Router & Axios

In this tutorial, I will show you how to build a Vue.js 2 CRUD Application to consume REST APIs, display and modify data using Vue 2, Vue Router and Axios. We will build a Vue.js front-end Tutorial Application in that:

- Each Tutorial has id, title, description, published status.
- We can create, retrieve, update, delete Tutorials.
- There is a Search bar for finding Tutorials by title.

## Technology
- vue: 2.6.10
- vue-router: 3.1.3
- axios: 0.19.0

## How to run
- `cd frontend`
- `cd vue-js-client-crud`
- `npm run serve`


![](imgs/django-vue-js-tutorial-rest-framework-crud-vue-client-overview.png)


|Methods    |Urls               |Actions                    |
|-----------|-------------------|---------------------------|
|POST       |/api/tutorials     | create new Tutorial       |
|GET	    |/api/tutorials	    |retrieve all Tutorials     |
|GET	    |/api/tutorials/:id	|retrieve a Tutorial by :id |
|PUT	    |/api/tutorials/:id	|update a Tutorial by :id   |
|DELETE	    |/api/tutorials/:id	|delete a Tutorial by :id   |
|DELETE	    |/api/tutorials	    |delete all Tutorials       |
|GET	    |/api/tutorials?title=[keyword] |	find all Tutorials which title contains keyword|


# References

- https://bezkoder.com/django-mongodb-crud-rest-framework/
- https://bezkoder.com/vue-js-crud-app/
