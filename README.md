The Setup so far...
Install Latest Python Version

pip install --user virtualenv

python -m virtualenv venv

to activate: 
-cd venv
-cd Scripts
-./activate.bat

to deactivate 
-./deactivate.bat

in the openvisionboard folder:
pip install django

to see if it worked: 
pip freeze
see as return:
-->pip freeze
asgiref==3.2.7
Django==3.0.5
pytz==2019.3
sqlparse==0.3.1


to create the project:
$ django-admin.py startproject openvisionboard

to launch the server from src folder:
python manage.py runserver

