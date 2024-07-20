# coding-project-template

After going to the server folder run the following 

```
pip install virtualenv
virtualenv djangoenv
source djangoenv/bin/activate
```

Install requirements 
```
python3 -m pip install -U -r requirements.txt
```

then 
```
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver
```
create user
```
python3 manage.py createsuperuser
```

```
docker build . -t nodeapp

docker-compose up
```