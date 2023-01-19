# Django Unit Test

## Setup the project

Clone the project using Git.

```sh
git@github.com:ravindra-devaliya/unit-test.git
cd unit-test
```

### Create .env file

```sh
cp .env.sample .env
```

### Migrate the database

```sh
python manage.py migrate
```

### Create the super user

```sh
python manage.py createsuperuser
```

The project is now running on http://127.0.0.1:8000.