# INSTALACIÓN DEL PROYECTO PRUEBA

### 1 Crear un entorno virtual en el root

`python -m venv venv`

### 2 Activar el entorno virtual

`source venv/Scripts/activate`

### 3 Instalar requirements.txt

`pip install -r requirements.txt`

### 4 Crear la varialble de entorno desde el root para flask migrations (git bash)

`export FLASK_APP=app.main:app`

### 5 Definir las variables requeridas en un .env. Las variables necesarias estan en .env.example

### 6 Inicializar la aplicacion flask....

`python -m app.main`
