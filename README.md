# django-ecommerce
## Sample website for testing CI/CD pipeline using jenkins and docker

Django Ecommerce Website

1. Clone repository using HTTPS and **cd** into the project
```
git clone https://github.com/Vedant-Mhatre/django-ecommerce.git
```
```
cd django-ecommerce
```

2. Create and start new virtual environment
```
python3 -m venv ecommerce
```
```
source ecommerce/bin/activate
```

3. Install all dependencies
```
pip install -r requirements.txt
```

4. Run initial migrations
```
python manage.py makemigrations
python manage.py migrate
```

5. Run tests
```
python manage.py jenkins
```

6. Start server
```
python manage.py runserver
```

Website will be available at [localhost:8000](http://localhost:8000/)
