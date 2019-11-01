Quick Start
############

准备环境::

    pipenv install
    pipenv shell


启动Flask::

    pipenv shell
    python app.py


启动Celery::

    pipenv shell
    celery worker -A app:celery -l info
