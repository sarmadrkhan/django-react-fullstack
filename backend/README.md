python -m venv env
env/Scripts/activate.bat
pip install -r requirements.txt
django-admin startproject backend
cd backend
python .\manage.py startapp api

update settings.py in backend/backend/
create serializers.py in backend/api/
update views.py
update urls.py in backend/backend/
create urls.py in backend/api/

python manage.py makemigrations
python manage.py migrate
python manage.py runserver
