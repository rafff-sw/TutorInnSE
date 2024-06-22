# TutorInnSE
Steps to run the website:
Go to Django TutorInn\djangoapp\newenv\Scripts
cmd
type "activate" to activate the virtual environment
go to Django TutorInn\djangoapp
type "python manage.py runserver"

Requirements (in virtual environment, if not downloaded yet)
pip install django
pip install pillow
pip install djangorestframework

Database Used:
PostgreSQL (pgAdmin 4) -> Create a database named "TutorInn Database"
Download link (For windows): https://www.pgadmin.org/download/pgadmin-4-windows/

Migrations (In virtual environment):
go to Django TutorInn\djangoapp
python manage.py makemigrations
python manage.py migrate
