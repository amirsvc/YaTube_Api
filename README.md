# **Учебный проект API_Yatube**

Автор: Исиналинов Амир https://t.me/Amir_Isinalinov

Язык программирования: Python

Используемые библиотеки и пакеты:

- django==2.2.16
- djangorestframework==3.12.4
- pytest==6.2.4
- pytest-django==4.4.0
- pytest-pythonpath==0.7.3
- requests==2.26.0
- Pillow==8.3.1
- sorl-thumbnail==12.7.0

## **Описание:**

REST API для моlелей приложения posts блога Yatube


  

### **Примеры запросов**



## **Как запустить проект:**

Клонировать репозиторий и перейти в него в командной строке:

git clone git@github.com:amirsvc/api_yatube.git

cd api_yatube

Cоздать и активировать виртуальное окружение:

python -m venv env

source env/script/activate

Установить зависимости из файла requirements.txt:

python -m pip install --upgrade pip

pip install -r requirements.txt

Выполнить миграции:

python manage.py migrate

Запустить проект:

python manage.py runserver
