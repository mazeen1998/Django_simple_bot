# Django_simple_bot
Django Simple bot with logs storage to Postgresql

Steps:
- Install all requirements through requirements.txt 'pip install -r requirements.txt' will do the thing (recomended to use a virtual environment)
- Use postgresql and change the credentials in settings.py and the <db_name> to be used for the project (log in to postgre and create a db and give the credentials)
- make migrations - 'python manage.py makemigrations'
- migrate - 'python manage.py migrate' and do sqlmigrate with the id
- python manage.y runsever ---> you are good to access

EP > localhost:port/chat (bot page) and loacalhost:port/logs (user click logs page )

