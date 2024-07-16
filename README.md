# recipe-app-api
Recipe API project

# To run tests in Docker:
docker compose run --rm app sh -c "python manage.py test"

# To create a new app:
docker compose run --rm app sh -c "python manage.py startapp core"

# To run linting 
docker compose run --rm app sh -c "python manage.py test && flake8"

## to avoid lines of linting use -> #noqa

