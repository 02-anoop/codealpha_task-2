# Django Social Network

A social media web-application with Django.

## Features :

<li>Sign Up, Login, OAuth 2.0(Google, Github), Logout, Forgot Password</li>
<li>Public Profile view</li>
<li>Create, Edit, Delete Posts with customized text, pictures and links</li>
<li>Like, Comment / Reply, Save and Search posts</li>
<li>Follow and Unfollow users to view their posts</li>
<li>Friend Request</li>
<li>Notifications</li>
<li>Chats using websockets</li>
<li>Video Calls</li>

## Demo


https://user-images.githubusercontent.com/64803043/118666705-02735600-b811-11eb-80f9-445bbe6e55c9.mp4


<a href="./demo/demo1.mp4">Video Link</a>

## Adding env variables

- Add env variables to ".test.env" and rename it to ".env"

- Add GOOGLE_RECAPTCHA_SECRET_KEY to both .env and the file 

- Add agora app_id to .env 

## Installation

```bash
    $ python -m venv venv
    $ source venv/Scripts/activate
    (venv) pip install -r requirements.txt
    (venv) cd Django_Social_Network_App
    (venv) python manage.py makemigrations
    (venv) python manage.py migrate
    (venv) python manage.py createsuperuser
    (venv) python manage.py runserver
```


## Add django-allauth config

https://django-allauth.readthedocs.io/en/latest/installation.html#post-installation



## Running Tests

To run tests, run the following command

```bash
  python manage.py test
```

## Deploy to Heroku

https://devcenter.heroku.com/articles/getting-started-with-python

https://realpython.com/django-hosting-on-heroku/
