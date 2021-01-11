# First Django


## Database
Django converts our Python code into sequel code. which can be executed on our database.
```
python3 manage.py makemigrations --dry-run
```

Applying built-in Django apps
```
python3 manage.py showmigrations
```

Setting up permissions
```
python3 manage.py migrate
```

Create login to look at tables and potentially make changes to them if needed
```
python3 manage.py createsuperuser
```