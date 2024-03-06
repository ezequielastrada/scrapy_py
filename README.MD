# PYTHON WEB SCRAPING - SCRAPY

Este proyecto está basado en el tutorial de [@josephkearney91](https://github.com/josephkearney91) ([VIDEO EN YT](https://www.youtube.com/watch?v=mBoX_JCKZTE))

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

Para inciar el proyecto primero debemos instalar las dependencias

`pip install -r requirements.txt`

## Configurar .env

postgre:  
`POSTGRES_HOST=''`  
`POSTGRES_USER=''`  
`POSTGRES_PASSWORD=''`  
`POSTGRES_DB=''`

scrapeops:  
`API_KEY=''`  
`FAKE_USER_AGENT_ENDPOINT=''`

## Comando para ejecutar spiders

`scrapy crawl bookspider`

## Comandos para exportar data

### Formato CSV

- Crea o sobrescribe el archivo  
`scrapy crawl bookspider -O myscrapeddata.csv`

- Crea o agrega al final del arvicho los resultados  
`scrapy crawl bookspider -o myscrapeddata.csv`

### Formato JSON

- Crea o sobrescribe el archivo  
`scrapy crawl bookspider -O myscrapeddata.json`

- Crea o agrega al final del arvicho los resultados  
`scrapy crawl bookspider -o myscrapeddata.json`