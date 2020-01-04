# A simple Django application

## Usage
http://localhost:8000  
http://localhost:8000/hello/{anyname}

## Useful Commands
pip3 install gunicorn  
sudo apt-get install -y nginx  
gunicorn --bind 0.0.0.0:8000 TestProject.wsgi:application  
sudo apt-get install -y supervisor  
sudo mkdir /var/log/gunicorn  
sudo supervisorctl reread  
sudo supervisorctl update
sudo supervisorctl status
