Проект Kittygram - социальная сеть для обмена фотографиями любимых питомцев.

## Описание проекта: 

Проект представляет собой програмный продукт, реализующий веб-приложение -
социальную сеть, в которой пользователи могут создавать профили своих домашних
питомцев, указывать их клички, добавлять фотографии и достижения своих любимцев,
указывать их окрас и год рождения. Пользователи могут просматривать созданные
друг другом профили питомцев.
Для добавления своих питомцев и просмотра профилей других питомцев пользователю
необходимо пройти регистрацию и последующую аутенфикацию

## Стек технологий:

  - asgiref==3.6.0
  - attrs==23.1.0
  - certifi==2023.5.7
  - cffi==1.15.1
  - charset-normalizer==3.1.0
  - coreapi==2.3.3
  - coreschema==0.0.4
  - cryptography==40.0.2
  - defusedxml==0.7.1
  - Django==3.2.3
  - django-templated-mail==1.1.1
  - djangorestframework==3.12.4
  - djangorestframework-simplejwt==4.8.0
  - djoser==2.1.0
  - gunicorn==20.1.0
  - idna==3.4
  - iniconfig==2.0.0
  - itypes==1.2.0
  - Jinja2==3.1.2
  - MarkupSafe==2.1.2
  - oauthlib==3.2.2
  - packaging==23.1
  - Pillow==9.0.0
  - pluggy==0.13.1
  - py==1.11.0
  - pycparser==2.21
  - PyJWT==2.7.0
  - pytest==6.2.4
  - pytest-django==4.4.0
  - pytest-pythonpath==0.7.3
  - python-dotenv==1.0.0
  - python3-openid==3.2.0
  - pytz==2023.3
  - requests==2.30.0
  - requests-oauthlib==1.3.1
  - six==1.16.0
  - social-auth-app-django==4.0.0
  - social-auth-core==4.4.2
  - sqlparse==0.4.4
  - toml==0.10.2
  - uritemplate==4.1.1
  - urllib3==2.0.2
  - webcolors==1.11.1

## Как запустить проект: 

##### Клонируем репозиторий: 

git clone https://github.com/dubininnik/infra_sprint1.git

### Запускаем backend:

cd infra_sprint1/backend

##### Cоздаем и активируем виртуальное окружение:

python3 -m venv env


source venv/bin/activate


python -m pip install --upgrade pip

##### Установливаем зависимости:

pip install -r requirements.txt


##### Выполняем миграции: 

python manage.py migrate


##### Запускаем backend: 


python manage.py runserver


### Запускаем frontend:


cd ./frontend


##### Устанавливаем зависимости для фронтенд-приложения:

npm i


##### Запускаем frontend:

npm run start


## Автор [Dubinin Nikolai](https://github.com/dubininnik/)
