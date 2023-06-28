# recipe-app-api
Recipe API project develop using Django Rest Framework

> to run flake8

```
docker compose run --rm app sh -c "flake8"
```

> to run tests

```
docker compose run --rm app sh -c "python manage.py test"
```

> to create new django project

```
docker compose run --rm app sh -c "django-admin startproject app ."
```
