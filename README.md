# Django Register & Login

## Setup
```
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
Open http://127.0.0.1:8000/ — you'll be redirected to login.
Register at /register/, login at /login/, logout via the button on the home page.
(Optional) `python manage.py createsuperuser` for /admin/.
