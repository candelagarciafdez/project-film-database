# Project: Film Database (ESP/EN)


`ESP`

En este proyecto, obtengo dos bases de datos de acceso público en IMDb y las combino para obtener información sobre la película y su puntuación en la página.

## Objetivos del proyecto

El objetivo del proyecto es **limpiar la base de datos**, en la que paso de aproximadamente 700k resultados a 300k , de los que me quedo con los 100 mejores.

El siguiente objetivo del proyecto, es **enriquecer la base de datos**. Para ello he *scrapeado* las webs de Metacritic (tanto las puntuaciones de la crítica como las de usuarios) y la web de RottenTomatoes.

## Herramientas utilizadas:

- `pandas`
- `json`
- `requests`
- `BeautifulSoup`
- `seaborn`
- `matplotlib`


## Problemas encontrados:

Una vez unidos los datos del *scraping* y los datos del análisis, vemos que coinciden muy pocos valores. Al hacer una gráfica con los años de las películas y las más votadas, observamos que el rango de fechas de las películas es diferente en cada una de las páginas, por eso apenas coinciden.

## Mejoras para el futuro:

Una mejora interesante, sería scrapear sobre los nombres de las películas directamente, y no sobre los resultados de las 100 mejores, ya que eso nos completaría totalmente los datos de nuestro dataset primario.



`EN`

In this project, I get two publicly accessible databases on IMDb and combine them to get information about the film and its score on the page.

### Project goals

The goal of the project is to clean the database, in which I go from approximately 700k results to 300k , of which I keep the top 100.

The next objective of the project is to enrich the database. To do this I have scraped the Metacritic websites (both review and user ratings) and the RottenTomatoes website.

### Tools used:

`pandas`
`json`
`requests`
`BeautifulSoup`
`seaborn`
`matplotlib`


### Problems encountered:
Once the scraping data and the analysis data are joined, we see that very few values coincide. When making a graph with the years of the movies and the most voted ones, we observe that the date range of the movies is different in each one of the pages, that's why they hardly coincide.

#### Improvements for the future:
An interesting improvement, would be to scrape over the names of the movies directly, and not over the results of the top 100, since that would completely complete the data of our primary dataset.


