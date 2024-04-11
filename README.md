# blog2
Blog App, 2nd time

## Overview
This code ...

## Installation

### Prerequisites

- Python 3.x
- Django 4.x.x


### Setup
The following setup preparations on the command line are required for the implementation.
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

## Access to each pages:
- `base.html` https://keita-sa.github.io/blog2/templates/base.html
- `home.html` https://keita-sa.github.io/blog2/templates/home.html
- `post_new.html` https://keita-sa.github.io/blog2/templates/post_new.html
