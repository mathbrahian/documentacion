# Brahian Munar CRUD

## Backend

```bash
git clone https://github.com/mathbrahian/AIT.git
cd AIT
virtualenv env
env\\scripts\\activate.bat
pip install -r requirements.txt
cd AITuring
python manage.py runserver
```

## Frontend

```bash
git clone https://github.com/mathbrahian/AIT-frontend.git
cd AIT-frontend
npm install
npm run serve
```

## Aplicación

Desde un navegador entrar a [localhost:8080](http://localhost:8080/), la aplicación consta de 4 pestañas, pero solo nos fijaremos en CRUD Filter y Add.

El CRUD Filter tiene las mismas características que un crud normal, pero además tiene:

1. paginación (botón previus y next)
2. ubicarse en cualquier página (botón go)
3. filtrar y colsultar información especifica (botón filter)
4. generar un reporte (botón report) en formato csv con los filtros añadidos con el boton filter

El add es una página sencilla que permite subir archivos csv, xsl, xslx. Estos deben de tener los encabezados:

1. name_client
2. country
3. city
4. category

En la carpeta AIT del backend se pueden encontrar archivos csv, xslx y xsl de prueba.
