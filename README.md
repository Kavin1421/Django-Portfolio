# SimpleDjangoPortfolio

This is a Simple Python Django Portolio.The portfolio is easy  just use "/admin"  to login into Django admin panel to change you personal info.



## Run these Commads
### Step 1
     pip install -r requirements.txt
### Step 2
     python manage.py migrate
     
### Step 4
     python manage.py createsuperuser
        
### Step 3
     python manage.py runserver

# Need to Host in AWS Follow Theses Steps:
### IN Ubuntu 
      1.sudo apt-get update
### Then
      2.git clone https://github.com/Kavin1421/Django-Portfolio.git
### for showing Directories
      3.ls -lrt
### change Directory
      4.cd Django-Portfolio
### See all Files
      5.ls -lrt
### install python
      6.sudo apt install python3-pip -y
### install all requirements
      Ex: pip install whitenoise
### To makemigrations
      7.python3 manage.py makemigrations
### To Migrate
      8.python3 manage.py migrate
### For Admin
      9.python3 manage.py createsuperuser

===>
Username (leave blank to use 'ubuntu'): Kavin

Email address: kkavinkumar24@gmail.com

Password: 1*4*@K****

Password (again): 1*4*@K****

Superuser created successfully.

### To run a Server
      10.python3 manage.py runserver 

### To run a Server in Custom Port

      11.python3 manage.py runserver 0.0.0.0:8000

### Important steps

* In security Groups we need to change inbound port

* Then all set your deployment was ready to launch!!!











