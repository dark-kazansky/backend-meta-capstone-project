## Steps to run the app

### 1. Install `pipenv`

```bash
pip install pipenv
```

### 2. Change the following information if you don't want to use them
```in littlelemon/settings.py
DATABASE = django.db.backends.mysql
USER     = admindjango
PASSWORD = employee@123!
HOST     = 127.0.0.1
PORT     = 3306
```

### 3. Install dependencies

```bash
pipenv install
```

### 4. Make migrations

```bash
py manage.py makemigrations
```

### 5. Migrate

```bash
py manage.py migrate
```

### 6. Run the app

```bash
py manage.py runserver
```

### To run tests

```bash
py manage.py test tests
```
