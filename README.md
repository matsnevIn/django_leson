# django_leson

Современная платформа для обучения. Прогрессивный взгляд на простые вещи.

Учебный проект системы управления обучением, который разработан при прохождений обучения на факультете "Python-разработка", портал GeekBrains, курс `Основы Django`.

## Стек

- Python > 3.7
  - isort, black, autoflake
  - Django < 3.3
  - Celery[Redis]
- VSCode
- SQLite 3

## Лицензия

MIT









pip install python-gettext
sudo apt-get install gettext


chmod -R 755 ./django_leson
chmod 777 /home/red/django_leson/braniaclms.sock



chmod -R 755 ./django_leson
chmod -R 755 ./static
chmod -R 755 ./media

!-->  chmod 777 /home/red/django_leson/braniaclms.sock  #решение проблемы с доступом 

(venv) red@red:~$ namei -l /home/red/django_leson/braniaclms.sock 
f: /home/red/django_leson/braniaclms.sock
drwxr-xr-x root root /
drwxr-xr-x root root home
drwxr-xr-x red  red  red
drwxrwxr-x red  red  django_leson
srwxrwxr-x red  red  braniaclms.sock