# deqode_webapp

This project contains the implementation of Deqode webapp.

# Technology Stack
We have used,
```
1. Python 3
2. Django Framework
3. sqlite3 Database
```

# Project Structure:

```
├── sshd_config
├── deqode_webapp
│   ├── settings.py: settings file for the project.
│   ├── __init__.py
│   ├── urls.py: url endpoints of linkedin scraper app
│   └── wsgi.py
├── manage.py
├── Readme.md: documentation file
├── requirements.txt: requirements needs to be install
├── app
│   ├── static: contains design data to load
│   ├── temaplates: contains design data to load
│   ├── __init__.py
│   ├── migrations: database migrations
│   ├── models.py: database models for app
│   ├── tests.py: test cases for view
│   ├── urls.py: urls for app
│   ├── forms.py: These forms are called by views
│   └── views.py: These views are called by urls
└── static
```

# Running Locally

First, clone the repository to your local machine:

```
git clone https://github.com/dev-appmonsters/deqode-webapp

cd deqode_webapp
```

Install the requirements:

```
pip install -r requirements.txt
```
