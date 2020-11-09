=====
#DRF JWT Authentication(Json Web Token)
=====

##This is a Django app to add JWT authentication to your DRF project. 

**Quick start
-----------
1. Move 'authentication' directory to your project directory.

2. Add "authentication" to your INSTALLED_APPS setting like this:
```
    INSTALLED_APPS = [
        ...
        'authentication',
    ]
```

3. Put AUTH_USER_MODEL = 'authentication.User' to your settings file.

4. Run ```python manage.py migrate``` to create user model.
