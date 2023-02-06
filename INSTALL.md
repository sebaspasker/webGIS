### Instalación

Para la instalación se recomiendo lo siguiente:

```bash
# Para instalar la webGIS lo ideal es que instalemos un entorno python.
$> pip3 install venv
$> python3 -m venv entorno_webGIS
$> cd entorno_webGIS 
$> source bin/activate
# Una vez creado hacemos clone en el entorno e instalamos los requerimientos
$> git clone https://github.com/sebaspasker/webGIS
$> cd webGIS
$> pip install -r dependencies.txt
# Creamos la base de datos dentro de django
$> cd webgis
$> python manage.py makemigrations
$> python manage.py migrate
$> python manage.py runserver

# Dentro del navegador corremos
http://localhost:8080/webgisapp
```

Los datos por desgracia son anónimos por lo que no se podrá observar una observación efectiva del funcionamiento del sistema con la información por puntos.



Para desinstalar:

```bash
&> rm -rI entorno_webGIS
```
