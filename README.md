# Django Models

## Create app called Blog and model called Post
Django has provided all template like admin, auth, sessions, and etc as default project template. All this template you can see at settings.py project in Application definition the name INSTALLED_APPS. If you runserver at first time make project, you will find message about unapplied migration(s). So to apply that you just need write in command python manage.py migrate And for database Django provide sqlite3.

The step: 
- Make project use command **django-admin startproject name_project**.
- Make apps example you want make apps the name 'blog', use command **python manage.py startapp blog**.
- 
