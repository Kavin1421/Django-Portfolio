# SimpleDjangoPortfolio

This is a Simple Python Django Portolio.The portfolio is easy  just use "/admin"  to login into Django admin panel to change you personal info.



## Run these Commands for Localhost 
### Step 1
     pip install -r requirements.txt
### Step 2
     python manage.py migrate
     
### Step 4
     python manage.py createsuperuser
        
### Step 3
     python manage.py runserver

### Run these Commands for Hosting
# Need to Host in AWS Follow These Steps:
### IN Ubuntu 
      sudo apt-get update
### Then
      git clone https://github.com/Kavin1421/Django-Portfolio.git
### for showing Directories
      ls -lrt
### change Directory
      cd Django-Portfolio
### See all Files
      ls -lrt
### install python
      sudo apt install python3-pip -y
### install all requirements
      Ex: pip install whitenoise
### To makemigrations
      python3 manage.py makemigrations
### To Migrate
      python3 manage.py migrate
### For Admin
      python3 manage.py createsuperuser

===>
Username (leave blank to use 'ubuntu'): Kavin

Email address: kkavinkumar24@gmail.com

Password: 1*4*@K****

Password (again): 1*4*@K****

Superuser created successfully.

### To run a Server
      python3 manage.py runserver 

### To run a Server in Custom Port

      python3 manage.py runserver 0.0.0.0:8000

### Important steps

* In security Groups we need to change inbound port

* Then all set your deployment was ready to launch!!!











