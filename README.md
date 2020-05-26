# flask-login
Authentication to Flask app with the Flask-Login 

### Running app locally

```
virtualenv flask-login-venv

# Windows
flask-login-venv\Scripts\activate
# Or Linux
flask-login-venv/bin/activate
```

Clone the git repo:

```
git clone https://github.com/celikfatih/flask-login.git
```

And install requirements:
```
pip install -r requirements.txt
```

And export flask app configuration:
```
export FLASK_APP=__init__.py:create_app

export FLASK_DEBUG=1
```

Run flask app:
```
flask run
```

Check browser address:
`
127.0.0.1:5000
`