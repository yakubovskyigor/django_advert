# DJANGO_ADVERT
___

## Installation

You can install this app on your working machine from source code:
```bash
# Step -- 1.
git clone --depth=1 --branch=master 'https://github.com/yakubovskyigor/django_advert.git'

# Step -- 2.
cd ./django_advert/

# Step -- 3.
docker-compose build

# Step -- 4.
docker-compose run web python manage.py migrate
docker-compose run web python manage.py createsuperuser

# Step -- 5.
docker-compose up
```

### URL

http://localhost:8000/admin  
http://localhost:8000/api/advert-list/  
http://localhost:8000/api/advert/\<int:pk\>/

