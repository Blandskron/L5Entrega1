# L5Entrega1

# Crear entorno virtual
```
python -m venv venv
venv\Scripts\activate
```
# Instalar Django
```
pip install django
```
# Crear proyecto y aplicacion
```
django-admin startproject seguridad
cd seguridad
python manage.py startapp autenticacionapp
```
# Editar Archivos en la app
° admin.py
° forms.py
° models.py
° views.py
# Editar Archivos en el proyecto
° setting.py
° urls.py
# Crear los templates
# Correr migraciones
```
python manage.py makemigrations
python manage.py migrate
```
# Crear super usuario
```
python manage.py createsuperuser
```
# Correr servidor
```
python manage.py runserver
```
