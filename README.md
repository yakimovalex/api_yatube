# api_yatube
api_yatube


python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt

python3 manage.py makemigrations

python manage.py migrate

python3 manage.py runserver