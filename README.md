# Hierarchical Data:

Python Django MPTT

# About This Project:

Build a simple Django server that uses MPTT models from django-mptt to create a Dropbox-esque web interface where you can create "folders" and "files" in an arbitrary structure and then display that structure. We won't actually be uploading anything, just making model instances and using them to represent real data. See the rubric for more detailed information.

### Follow These Steps:

1. export PATH="$HOME/.poetry/bin:$PATH"
2. poetry init
3. poetry install django-mptt
4. python `manage.py` makemigrations files
5. python `manage.py` migrate
6. python `manage.py` createsuperuser
7. pythom `manage.py` runserver
