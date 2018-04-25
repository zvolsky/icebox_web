web: gunicorn config.wsgi:application
worker: celery worker --app=icebox_web.taskapp --loglevel=info
