# ChatApp

Install virtual enviroment
virtualenv -p python3 .

activate bin
source bin/activate

pip3 install django

pip3 install channels

pip3 install channels_redis

python3 manage.py migrate

python3 manage.py runserver
