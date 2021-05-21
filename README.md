# Project_2_Data_Extraction
Proyecto de extracción de datos bajo las técnicas de scraping utilizando una API pública.


## Introducción

El objetivo de éste proyecto es crear un archivo CSV que contenga datos extraídos de una página web mediante las técnicas de WEB SCRAPING o utilizando API públicas, además se debe realizar la limpieza de información para tratar en la medida de lo posible, genera una base de datos lista para analizar.

## Desarrollo

Como primer paso se realizó búsqueda de una página web que para cumplir con el objetivo, finalmente se consiguió una API de la página https://www.musixmatch.com

Para consumir el API publicado por ésta página es necesario realizar un registro para generar una CLAVE que es utilizada para poder hacer las solicitudes.

El siguiente pasó fue leer la documentación para conocer los métodos pulicados así como los datos de entrada que se necesitan para poder consultar información.

Las primeras pruebas de consumo de APIs se realizaron con la herramienta POSTMAN con el objetivo de conocer como se arma la cadena de solicitud, así como la respuesta que se obtiene, los datos que proporciona cada método y que información sería más útil para el objetivo de este proyecto.

Se definieron varias funciones para 4 diferentes consultas, se creó un archivo llamado enviroment.env para alojar la clave utilizada para consumir los servicios.

Finalmente se creó una carpeta llamada OUTPUT donde se alojan los archivos tipo CSV con la información recuperada de los diferentes métodos de la API consumida.

## Entregables
- Carpeta CONFIG, aloja el archivo envireoment.env
- Carpeta CODE, contiene el archivo ipynb del código fuente.
- Carpeta OUTPUT, contiene el resultado de la extracción en archivos CSV

## Fuentes
Documentación de APIs de Musixcmatch https://developer.musixmatch.com/
URL base para solicitud de información http://api.musixmatch.com/ws/1.1/



