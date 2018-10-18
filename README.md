# Google-And-Facebook-Authentication
This is the most basic implementation of Google and Facebook authentication using the django-allauth package

For Facebook authentication other packages were installed since it requires our website to be HTTPS
This can be done through the command:
pip install django-extensions Werkzeug pyOpenSSL (which is already installed in the virtual environment)
Werkzeug is basically a kickass debugger when working with HTTPS

## How to run this
Clone this repo and enter into virtual environment ( named venv ).
#### Step to activate virutal environment ( For ubuntu )
Open your terminal and change your working directory to Google-And-Facebook-Authentication and then type:
source venv/bin/activate (in your terminal)
#### Runnning the website
Since Facebook authentication is only possible with https therefore instead of running our website through python manage.py runserver command we run our website through the command python manage.py runserver_plus --cert-file /tmp/cert.<br>
Google authentication will also work with https so don't forget to run https debugger through the command python manage.py runserver_plus --cert-file /tmp/cert
