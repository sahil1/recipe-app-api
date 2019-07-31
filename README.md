# recipe-app-api
Recipe App API

```
docker-compose run app sh -c "django-admin.py startproject app ."

docker-compose run app sh -c "python manage.py test"
docker-compose run --rm app sh -c "python manage.py test"

docker-compose run --rm app sh -c "python manage.py test && flake8"

docker-compose run app sh -c "python manage.py startapp core"
```
