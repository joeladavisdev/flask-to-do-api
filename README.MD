# Python flask TODO Api

Python Flask backend app for keeping track of todos. It uses a flask

> Create Database
- Make sure your in your pipenv shell and hop into a python repl and run these commands.  After you run these commands you will see an app.sqlite file.
```
$ pipenv shell
$ python
>>> from app import db
>>> db.create_all()
```