web: gunicorn config.wsgi:application
worker: celery worker --app=greg.taskapp --loglevel=info
