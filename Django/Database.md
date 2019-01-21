# Install the preferred database i.e `mysql`, `postgres`

install psycopg2 if using postgres `pip install psycopg2`
  
# Set database settings on settings.py 

```py
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'unah',
        'USER': ' sifuma',
        'PASSWORD': '',
        'HOST': 'localhost'
        
    }
}
```

Run `python manage.py migrate`  . All migrations are moved to the database i.e user authenrication, sessions, groups e.t.c. 




