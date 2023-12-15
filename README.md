# Hi Django

Trying out [Django](https://www.djangoproject.com/) 5.0 for fun and profit
by following a [tutorial](https://docs.djangoproject.com/en/5.0/intro/tutorial01/).

## Start Server

```shell
python manage.py runserver 8000
```

## Open app in browser

- <http://127.0.0.1:8000/polls/>
- <http://127.0.0.1:8000/admin/>

## Run shell

```shell
python manage.py shell
```

## Make DB migrations for polls app 

```shell
python manage.py makemigrations polls
```

## Show DDL

```shell
python manage.py sqlmigrate polls 0001
```

## Apply DB migrations

```shell
python manage.py migrate
```

## Create an admin user

```shell
python manage.py createsuperuser
```
