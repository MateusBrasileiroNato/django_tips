# Creating Django project:

cd "chosen_folder"
django-admin startproject "project_folder"
cd "project_folder"
python manage.py startapp "files_folder"

# Migrations

cd "project_folder"
python manage.py makemigrations
python manage.py migrate

# Testing

python manage.py runserver
