#API для проекта yatube

## Технологии:
Python 3.7
Django 2.2.19

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/pvlvnk/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```

```
source venv/scripts/activate
```

```
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 yatube_api/manage.py migrate
```

Запустить проект:

```
python3 yatube_api/manage.py runserver
```
