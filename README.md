# 🕸 Web Scraping — Books to Scrape_We love being scraped!

Vamos a realizar un ejercicio de extracción, análisis y visualización de datos a partir del sitio [books.toscrape.com](http://books.toscrape.com) propuesto por [Alain](https://github.com/alain-coder1) durante el Bootcamp de Data Analyst de [Factoría F5](https://factoriaf5.org/).


## Stack tecnológico 🛠️

| Librería | Versión | Uso |
|---|---|---|
| `requests` | ≥2.x | Realización de peticiones HTTP |
| `beautifulsoup4` | ≥4.x | Parseo y extracción del HTML |
| `pandas` | ≥2.x | Estructuración, limpieza y consulta de datos |
| `matplotlib` | ≥3.x | Generación de gráficos |
| `csv`  | — | Exportación de los datos extraídos |
<br>


![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python&logoColor=white)
![requests](https://img.shields.io/badge/requests-2.x-FF6B6B?style=flat)
![BeautifulSoup4](https://img.shields.io/badge/BeautifulSoup4-4.x-4B8BBE?style=flat)
![pandas](https://img.shields.io/badge/pandas-2.x-150458?style=flat&logo=pandas&logoColor=white)
![matplotlib](https://img.shields.io/badge/matplotlib-3.x-11557C?style=flat)
![CSV](https://img.shields.io/badge/export-CSV-brightgreen?style=flat)



## Instalación de librerías

```bash
pip install requests beautifulsoup4 pandas matplotlib
```


## Datos extraídos

Por cada libro se obtienen los siguientes campos:

- `title` — título del libro
- `price` — precio en libras esterlinas
- `rating` — valoración (1–5 estrellas)
- `stock` — disponibilidad en stock

## Ejemplos de análisis

- Distribución de precios
- Análisis de valor: libro con 4 ´5 estrellas y precio inferior a £20.
- Estudiamos la relación entre longitud del título y el precio.
- Correlación entre Rating y precio y su gráfico.
- Buscamos libros con máxima puntuación y por debajo del precio medio; también los 10 libros más baratos de entre los que tienen 5 estrellas.
- Buscamos los 10 libros "Premium", con un coste más alto, y los visualizamos en un gráfico de Piruleta (Lollipop Chart).

## Fuente de datos

[books.toscrape.com](http://books.toscrape.com) — sitio web creado específicamente para practicar técnicas de web scraping.

## Notas

> Este proyecto tiene fines exclusivamente educativos. El sitio books.toscrape.com está diseñado para ser scrapeado libremente.
