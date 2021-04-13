# Criando projeto no Visual Studio Code:

cd "pasta"
django-admin startproject "pasta_projeto"
cd "nome"
python manage.py startapp "subpasta_arquivos"

# Migrações do projeto

cd "pasta_projeto"
python manage.py makemigrations
python manage.py migrate

# Testando 

python manage.py runserver
