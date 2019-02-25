# Django is a high level framework that uses concept of Apps.

# Sites that use/used Django
1. Disqus 
2. Instagram
3. Bitbucket
4. Firefox Help Site
5. Pinterest
6. EventBrite
7. Onion e.t.c

# Requirements
Python and Django

# Step 1
. Create a projects folder and cd into it. 
. Create a virtualenvironment forse code isolation from the rest of the system
. Activate the virtualenvironment . 
     `source/env/bin/activate`

# Step 2
. Install Django
   `pip install Django`
. Start project
  `django-admin startproject djangopractice`
The files created i.e:
  . __init__.py - empty file that remains like that, treats directory as containing packages
  . settings.py - has all settings of the application 
    ` DEBUG = True ` : set for development which we will use for now
    ` ALLOWED_HOSTS` : domain names to be used in the applications
    ` INSTALLED_APPS`: Any application you create you need to add in                       this array
    ` MIDDLE_WARE` : For authentication and has a specific order

  . urls.py - Setting up routes. Url patterns use regular expressions.              Each app has it's own url file
  . wsgi.py - primary development platform for django 
  . manage.py - the Cli client, wrapper of django-admin. It's localised to this specific project that's used to run migrations, run dev serever e.t.c
  . models.py - Models are created here
  . views.py  -  Where index, details are created. Templates can be loaded here.