# blog2
Blog App, 2nd time

## Overview
This code ...

## Features

- Route by a combination of paths and **HTTP methods** such as GET, POST, PUT and DELETE.
- Test web APIs with Postman. 

## Installation

### Prerequisites

- Python 3.x
- Django 4.x.x


### Setup
To set up the routes which mean endpoints, you need to install the `gorilla/mux`. You can do this by running:
```
# macOS
% mkdir blog
% cd blog
% python3 -m venv .venv
% source .venv/bin/activate
(.venv) % python3 -m pip install django~=4.0.0
(.venv) % django-admin startproject django_project .
(.venv) % python3 manage.py startapp blog
(.venv) % python3 manage.py migrate
```

pages:

- `base.html` https://keita-sa.github.io/blog2/templates/base.html
- `home.html` https://keita-sa.github.io/blog2/templates/home.html
- `post_new.html` https://keita-sa.github.io/blog2/templates/post_new.html
