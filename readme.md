# About me
A Django app to track corporate assets such as phones, tablets, laptops
and other gears handed out to employees.
# Installation  
## Migrate and createsuperuser
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser  
## Run Server  
python manage.py runserver
## API endpoint access
http://localhost:8000/api/companies/
http://localhost:8000/api/employees/
http://localhost:8000/api/devices/
http://localhost:8000/api/devicelogs/