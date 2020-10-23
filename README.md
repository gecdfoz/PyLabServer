# PyLabServer

## Introduction

Features

* Simple flask application using application factory, blueprints


Used packages :

* [Flask](http://flask.pocoo.org/)
* [Flask-RESTful](https://flask-restful.readthedocs.io/en/latest/)
* [Flask-Migrate](https://flask-migrate.readthedocs.io/en/latest/)
* [Flask-SQLAlchemy](http://flask-sqlalchemy.pocoo.org/2.3/)
* [Flask-Marshmallow](https://flask-marshmallow.readthedocs.io/en/latest/)
* [Flask-JWT-Extended](http://flask-jwt-extended.readthedocs.io/en/latest/)
* [marshmallow-sqlalchemy](https://marshmallow-sqlalchemy.readthedocs.io/en/latest/)
* [passlib](https://passlib.readthedocs.io/en/stable/)
* [tox](https://tox.readthedocs.io/en/latest/)
* [pytest](https://docs.pytest.org/en/latest/)
* [factoryboy](http://factoryboy.readthedocs.io/en/latest/)
* [dotenv](https://github.com/theskumar/python-dotenv)
* [apispec](https://github.com/marshmallow-code/apispec)


## Usage

* [Installation](#installation)
* [Configuration](#configuration)
* [Authentication](#athentication)
* [Running tests](#running-tests)
* [Changelog](#changelog)


### Installation

#### Install 


You can install it using this command : `pip install cookiecutter`


#### Install project requirements

Let's say you named your app `myapi` and your project `myproject`

You can install it using pip :

```
cd myproject
pip install -r requirements.txt
pip install -e .
```

### Configuration



### Authentication


### Running tests


#### Using pytest directly

If you want to run pytest manually without using tox you'll need to install some dependencies before

```
pip install pytest pytest-runner pytest-flask pytest-factoryboy factory_boy
```

Then you can invoke pytest

```
pytest
```

Note that tox is setting environment variables for you when testing, but when using pytest directly that's not the case. To avoid setting up env variables each time you run pytest, this cookiecutter provide a `.testenv` file that contains default configuration for testing. Don't forget to update it if your local env doesn't match those defaults.


## Changelog

### 23/10/2020 - v 0.5

- Initial project config.
