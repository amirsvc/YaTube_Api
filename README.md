# **Учебный проект API для Yatube**

Автор: Исиналинов Амир https://t.me/Amir_Isinalinov

Язык программирования: Python 3.7

Используемые библиотеки и пакеты:

- Django==2.2.16
- pytest==6.2.4
- pytest-pythonpath==0.7.3
- pytest-django==4.4.0
- djangorestframework==3.12.4
- djangorestframework-simplejwt==4.7.2
- Pillow==8.3.1
- requests==2.26.0


## **Описание:**

REST API для моделей приложения posts блога Yatube
  

## **Как запустить проект:**

- Клонировать репозиторий и перейти в него в командной строке:
~~~
git clone git@github.com:amirsvc/api_final_yatube.git
~~~
~~~
cd api_final_yatube    
~~~

- Cоздать и активировать виртуальное окружение:
~~~
python -m venv env
~~~
~~~
source env/script/activate
~~~
- Установить зависимости из файла requirements.txt:
~~~
python -m pip install --upgrade pip
~~~
~~~
pip install -r requirements.txt
~~~
- Выполнить миграции:
~~~
python manage.py migrate
~~~
- Запустить проект:
~~~
python manage.py runserver
~~~
- Получить документацию по API:

http://127.0.0.1:8000/redoc/