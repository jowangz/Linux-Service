# Linux-Server-Configuration

## IP address: 52.36.150.173 port: 2200
## Complete URL: ```52.36.150.173```
## Software installed and configuration changes made:
* adduser grader
* installed finger
* changed ssh port
* add sudo permission to user grader
* update all packages
* configured UFW deny all incoming connections
* configured UFW allow incoming connections for SSH(port 2200), HTTP(port 80), and NTP(port 123)
* enable UFW
* check timezon UTC
* install apache2
* install apache2-mpm-prefork apache2-prefork-dev
* install python-pip
* install mod_wsgi
* install PostgreSQL
* add file catalog.wsgi
* install virtualenv
* a2enmod wsgi
* clone catalog-app
* install flask
* install sqlalchemy
* install requests
* install oauth2client
* install dict2xml
* install libapache2-mod-wsgi
* add sites-abailable/catalog.conf
* change application.py name to __init__.py
* install python-psycopg2
* install postgresql postgresql-contrib
* create user catalog with password catalog
* create database categoryitemwithuserandpicture
* edit __init__.py and database_setup.py postgresql path
* a2ensite catalog
* add AWS instance to google credentials
* restart apache2

## Third party resources:
* http://killtheyak.com/use-postgresql-with-django-flask/
* https://discussions.udacity.com/t/project-5-resources/28343
* https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-14-04
