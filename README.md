# userapp
- first download postgres database and pgadmin
- commands to run the django app
- first make virtual environment for the project 
  - python3 -m venv dj
  - for linux user - source dj/bin/activate
  - for windows user - dj\Scripts\activate
       
0. pip install -r requirements.txt
1. python manage.py makemigrations
2. python manage.py migrate
3. python manage.py collectstatic
4. python manage.py createsuperuser
   - username
   - email
   - password
5. python manage.py runserver
   ![This is image](https://raw.githubusercontent.com/Kabirdas2022/userapp/master/static/login.png)
   - enter email and password to get enter
   - click on add staff on left 
   ![image after clicking on add staff](https://raw.githubusercontent.com/Kabirdas2022/userapp/master/static/add_staff.png)
This is a simple django project for user management system, it contains three type of users 
- Admin
- HR
- Employee
