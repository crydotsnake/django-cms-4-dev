# djangoCMS 4 Project

## Setup:

Create a virtual python envoirement:

```bash
mkvirtualenv cms4core
```

Or if you dont have virtualenvwrapper installed:

```bash
virtualenv cms4core
```

## Install requirements

```bash
pip install -r requirements.txt
```

## Run migrations

```bash
python manage.py migrate
```

## Create admin user

```bash
python manage.py createsuperuser
```

## Start development server

```bash
python manage.py runserver
```

## Check your installation

You can check your installation for any erros with:

```bash
python manage.py cms check
```