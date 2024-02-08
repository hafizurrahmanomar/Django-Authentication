# Django-Authentication 

Usage
=================

First clone this repo and go to the project root.

    $ git clone https://github.com/hafizurrahmanomar/Django-Authentication.git
    $ cd Django-Authentication


    $ pip install django
    


Activate the virtual environment by the following command:


***On Linux***

    $ source venvName/bin/activate
    
***On Windows***

If you are using git bash

    $ source venvName/Scripts/activate
    
If you are using CMD

    $ cd venvName/Scripts
    $ activate
    $ cd ../../
    

Finally, you have to make migrations to get the app started and create a new superuser to interact with the admin dashboard.
So run the following commands as follows:

    $ python manage.py migrate
    $ python manage.py createsuperuser
      $ Hafizur/Hafiz@#/hafizurrahman@gmail.com

So after successful completion of these you are ready to run the application by the following command:

    $ python manage.py runserver
  

***NB: you have to change the following configurations in settings.py to send email for password reset***


    $ EMAIL_BACKEND = "django.core.mail.backends.smtp.EmailBackend"
    $ EMAIL_USE_TLS = True
    $ EMAIL_HOST = "smtp.gmail.com"
    $ EMAIL_HOST_USER = "example@gmail.com"
    $ EMAIL_HOST_PASSWORD = "yourapppassword"
    $ EMAIL_PORT = 587


# Django-Authentication
# Django-Authentication
