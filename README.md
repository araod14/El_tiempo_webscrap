# Webscraping pagina de noticias: Eltiempo.com.ve
###Objetivo
El programa, guardara los titulares, cuerpo de la noticia en un archivo .txt y almacenara en una carpeta con la fecha de origen de la publicación

**Contenido**

[TOC]


###Links

`link del repositorio` : <https://github.com/araod14/El_tiempo_webscrap/>

`Pagina noticiero digital El tiempo` : <https://eltiempove.com/>


Cuenta twitter ElTiempove @eltiempove

###Requerimientos

- Conda
- Terminal Linux o subsistema Linux


###Instalar requerimientos con Conda
Descarga web scraper del repositorio
`git clone https://github.com/araod14/El_tiempo_webscrap.git`

Ir a la carpeta del web scraper
`cd El_tiempo_webscrap`

Crear y ambiente virtual con conda
`conda env create -n webscraper -f requirements.txt`

Activar ambiente virtual
`conda activate webscraper`

Correr el programa
`python3 eltiempo_web_scrapper.py`
