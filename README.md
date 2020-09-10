# Django-crm
A Customer Relationship Management (CRM) system helps manage customer data.

## Installation:

**1.Clone Repo**
```sh
git clone https://github.com/oussama-seme-elayne/Django-crm.git
```
**2.Setup Virtualenv**
```sh
virtualenv env
source env/bin/activate
```
**3.Install Requirements**
```sh
cd requirements.txt
pip install -r requirements.txt
```
**4.Migrate Database**
```sh
python manage.py makemigrations
python manage.py migrate
```
**5.Create User**
```sh
python manage.py createsuperuser
```
**6.Run Server**
```sh
python manage.py runserver
```
