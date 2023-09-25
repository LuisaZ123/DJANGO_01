# DJANGO_01
### 1. Introducción

Este proyecto es una aplicación web desarrollada utilizando el framework Django.

### 2. Requisitos

- Python 3.8
- Django 3.1

### 3. Instalación

1. Instalar Django en la consola de python
pip install django


2. Crear un entorno virtual:

python -m venv venv
​
3. Activar el entorno virtual:

- En Windows:
\venv\Scripts\activate.bat

- En Linux o macOS:
​
source venv/bin/activate

4. Instalar las dependencias:
​
pip install -r requirements.txt
​
5. Ejecutar las migraciones:

python manage.py migrate

6. Crear un superusuario:

python manage.py createsuperuser

7. Ejecutar el servidor de desarrollo:

python manage.py runserver
​
### 4. Uso

1. Acceder a la aplicación web a través de un navegador web utilizando la siguiente URL:

http://localhost:8000

2. Iniciar sesión como superusuario utilizando las credenciales proporcionadas al crear el superusuario.

