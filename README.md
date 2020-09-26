# RUCS24's Website

Our website is written in Python using Flask, a light-weight micro-framework
for web-development. The project is set up to use
[pipenv](https://pipenv-fork.readthedocs.io). Follow these instructions to set up a testing
instance of the web application on your own computer, assuming you already have
Python and `pip` set up.

## Environment Set Up

### Linux and Mac

```
$ export FLASK_APP=rucs24
$ export FLASK_ENV=development
$ flask run
```

### Windows (cmd)

```
> set FLASK_APP=flaskr
> set FLASK_ENV=development
> flask run
```

### Windows (PowerShell)
```
> $env:FLASK_APP = "flaskr"
> $env:FLASK_ENV = "development"
> flask run
```

## Application Set Up

1. Install `pipenv` with `pip install --user pipenv`
2. Install project dependencies with `pipenv install`
3. Run the project with `pipenv run flask run`
4. Navigate to [https://localhost:5000](https://localhost:5000)
