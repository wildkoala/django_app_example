# django_app_example
Quickly hacking something together in 30 mins as an example

You could read the documentation here: https://docs.djangoproject.com/en/3.1/intro/tutorial01/

But don't hurt yourself. Here's the skinny on making a new Django app.

# Make sure you have django
pip3 install django

# Start your project
django-admin startproject <insert_project_name_here>

^ this bad boy is going to give you a bunch of files and folders that Django uses. 
It's a lot to take in but don't be intimidated, we won't use 75% of it in the beginning anyway.
Notice I said PROJECT too, not APP. Projects can have multiple apps, but again, that's for later.

# Go into your new project
cd <insert_project_name_here>

# Start the basic app
python3 manage.py runserver

Bam - look at you. Running a django app, how neat!
