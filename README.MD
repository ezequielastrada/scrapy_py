# PYTHON WEB SCRAPING - SCRAPY

Este proyecto esta basado en el tutorial de [@josephkearney91](https://github.com/josephkearney91) ([VIDEO EN YT](https://www.youtube.com/watch?v=mBoX_JCKZTE))

En esta ocacion utilizo Scrapy en python donde he extraido datos de la web [https://books.toscrape.com/](https://books.toscrape.com/)

Temas aprendidos:
- Instalar python en Windows
- Configurar entorno virtal Python en Windows
- Instalar Scrapy
- Crear un proyecto Scrapy
- Estructura general del proyecto Scrapy
- Scrapy Spiders
- Scrapy Items
- Scrapy Item Pipelines
- Scrapy Middleware
- Scrapy Settings
- Guardar datos en archivos y bases de datos

## Para inciar el proyecto primero debemos instalar las dependencias

`pip install -r requirements.txt`


## COMANDOS PARA EXPORTAR DATOS

`scrapy crawl bookspider -O myscrapeddata.json`

`scrapy crawl bookspider -O myscrapeddata.csv`