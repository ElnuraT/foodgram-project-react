    # FOODGRAM

FOODGRAM это удобный сайт для размещения и поиска рецептов.

### Технологии:

Python, Django, Docker, Gunicorn, NGINX, PostgreSQL, Yandex Cloud.

### Для запуска проект необходимо:

- Клонировать репозиторий:
```
git@github.com:ElnuraT/foodgram-project-react.git
```
- Создание виртуального окружения и установка зависимостей
```bash
python -m venv venv (windows)
python3 -m venv venv (linux)
. source venv/Scripts/activate (windows)
. source venv/bin/activate (linux)
pip install --upgade pip
pip install -r -requirements.txt
```
- Примените миграции и соберите статику
```bash[README.md](README.md)
python manage.py makemigrations
python manage.py migrate
python manage.py collectstatic --noinput
```
- Наполнение базы данных ингредиентами и тегами
```bash
python manage.py load_ingredients

```

```
- Запуск сервера
```bash
python manage.py runserver
```

### Работа с api
- В проекте уже создана админка, несколько рецептов и юзеров, а также в базу были добавлены ингредиенты для более удобной работы.

- Админка доступна по ссылке [http://127.0.0.1:8000/admin/].

```
admin:
username: Elnura
password: Adema2016