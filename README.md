# Buscador-de-noticias-NewsAPI
Script para hacer scrapping de noticias utilizando la API de Google: https://newsapi.org/docs
## Endpoints
- Everything/v2/everything:Busca todos los artículos publicados por más de 80 000 fuentes diferentes, grandes y pequeñas, en los últimos 5 años. Este endpoint es ideal para el análisis de noticias y el descubrimiento de artículos.
- top-headlines/v2/top-headlines: Devuelve titulares de noticias de última hora para países, categorías y editores singulares. Esto es perfecto para usar con tipos de noticias o en cualquier lugar donde desee usar titulares de noticias actualizados en vivo.

También hay un endpoint que se puede usar para recuperar un pequeño subconjunto de los editores que podemos escanear:
- Sources/v2/top-headlines/sources: devuelve información (incluido el nombre, la descripción y la categoría) sobre las fuentes más notables disponibles para obtener los principales titulares. Esta lista podría canalizarse directamente a sus usuarios al mostrarles algunas de las opciones disponibles.
