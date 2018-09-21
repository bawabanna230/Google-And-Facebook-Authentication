# Google-And-Facebook-Authentication
This is the most basic implementation of Google and Facebook authentication using the django-allauth package

## How to run this
Clone this repo and enter into virtual environment ( named myenv ).
#### Step to activate virutal environment ( For ubuntu )
1. Open your terminal and change your working directory to Google-And-Facebook-Authentication and then type:
source venv/bin/activate (in your terminal)
#### Runnning the website
2. Since Facebook authentication is only possible with https domain therefore instead of running our website through python manage.py runserver command we run our website through the command python manage.py runserver_plus --cert-file /tmp/cert
