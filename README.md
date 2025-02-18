🎵 **Análisis del Top 50 de LATAM en Spotify – Web Scraping & API**

Este proyecto extrae y analiza las canciones más populares en Latinoamérica, utilizando web scraping para obtener los IDs de las canciones del Top 50 de cada país, y luego accediendo a la API de Spotify para recopilar información detallada sobre cada canción.

📊 Se generaron visualizaciones para analizar la popularidad, los artistas más recurrentes y la distribución de las canciones en los rankings.

🚀 Flujo del Proyecto

1️⃣ Extracción de Datos

Se usó web scraping con BeautifulSoup y requests para obtener los IDs de las canciones del Top 50 de Spotify en LATAM.
Se accedió a la API de Spotify con spotipy para obtener:

🎤 Artista

🔥 Popularidad

📍 País de origen del ranking

🎶 Posición en el Top 50

2️⃣ Procesamiento y Análisis

Se estructuraron los datos en un DataFrame con Pandas.

Se calcularon estadísticas sobre la frecuencia de los artistas en el ranking y la distribución de la popularidad.

3️⃣ Visualización de Datos

📈 Gráficos generados con Seaborn y Matplotlib:

✔️ Canciones más populares 🔥

✔️ Artistas con más apariciones en el Top 50 🎤

✔️ Distribución de canciones en el ranking por artista 🎶

🛠 Tecnologías Utilizadas

Python 3.11.9

Requests & BeautifulSoup – Web Scraping de los datos del Top 50.

Spotipy (API de Spotify) – Obtención de información de canciones.

Pandas – Manipulación y análisis de datos.

Seaborn & Matplotlib – Creación de visualizaciones interactivas.
