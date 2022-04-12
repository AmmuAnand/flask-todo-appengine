# flask-todo-appengine
This is a Simple Flask todo application with SQLAlchemy and SQLite database deployed in app engine


### Setup
Create project with virtual environment

```console
$ mkdir myproject
$ cd myproject
$ python3 -m venv venv
```

Activate it
```console
$ . venv/bin/activate
```

or on Windows
```console
venv\Scripts\activate
```

Install Flask
```console
$ pip install Flask
$ pip install Flask-SQLAlchemy
```

Set environment variables in terminal
```console
$ export FLASK_APP=app.py
$ export FLASK_ENV=development
```

or on Windows
```console
$ set FLASK_APP=app.py
$ set FLASK_ENV=development
```

Run the app
```console
$ flask run
```
Application running on Google App engine
```console
$ gcloud app deploy
```
Application running in http://ferrous-coda-346414.uc.r.appspot.com/
