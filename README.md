# pyexpress_django

- Python installation
- pip installation
  - Click [here](https://bootstrap.pypa.io/get-pip.py)
  - Choose "Save file" option.
  - Open your terminal (CTRL+ALT+T) and run following two commands.
  - <pre>cd ~/Downloads</pre>
  - <pre>sudo python ~/Downloads/get-pip.py</pre>
  - Now you have python package manager installed on your system. Next we will download Django
- [Django installation](https://docs.djangoproject.com/en/1.10/topics/install/)
  <pre>
  sudo pip install django
  </pre>
- Code editor
  - Sublime Text 2
  - [Atom.io](https://atom.io)
  - Eclipse
  - Pycharm
- Introduction to Django
- Creating first django project
  <pre> 
  django-admin startproject mysite . 
  </pre>
- Understanding the structure of a Django project. : This will include making changes to settings.py, setting up database and starting the web server. End of this, user should be able see the "It worked" page.
  <pre>
    pyexpress_django
    ├───manage.py
    └───mysite
            settings.py
            urls.py
            wsgi.py
            __init__.py
  </pre>
- Django Models : Example driven model development.
- Django Admin : Details on importance of Django admin site and how it shows DB structure. More [here](https://docs.djangoproject.com/en/1.10/ref/contrib/admin/)
- Django Urls : How urls work. May include some details of [regex](https://docs.djangoproject.com/en/1.10/topics/http/urls/), depending upon audience.
- Django Views : Mapping of Urls to Views. Create and write some Py logic.
- Django Templates : Introduction to HTML. Display the changes made in the view defined previously. Some more information on templating engines if time permits.
- Django Forms
- Further Readings and References to follow.
