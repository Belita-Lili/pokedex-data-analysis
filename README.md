# Pokemons
Para este proyecto se va ha hacer una versión de uno de los videojuegos más famosos de la historia: Pokémon. Tendrás que usar todas tus habilidades de Pythonista creando clases, instancias, métodos, condicionales y ciclos para lograr tu meta.

Este código en Python tiene como objetivo principal obtener datos de Pokémon de la API pública de Pokémon (pokeapi.co), realizar web scraping para obtener información adicional de las próximas fechas de lanzamiento de juegos de Pokémon, y luego combinar y procesar estos datos para crear tres tablas:

1. Tabla de Pokémon: Esta tabla contiene información básica sobre cada Pokémon, incluyendo su ID, nombre, generación, tipo, habilidades, tasa de captura, felicidad base y movimiento inicial. Se utilizan las bibliotecas requests y pokebase para obtener datos de la API de Pokémon.
2. Tabla de Características: Esta tabla combina los datos de Pokémon con información sobre la generación y la región en la que se encuentran. También incluye la clase del Pokémon, su tasa de captura, felicidad base, habilidades y región. Se utiliza web scraping con la biblioteca BeautifulSoup para obtener las fechas de lanzamiento de juegos de Pokémon.
3. Tabla de Estadísticas: Esta tabla contiene estadísticas de batalla de cada Pokémon, incluyendo su movimiento inicial, ataque, defensa, HP, ataque especial, defensa especial y velocidad.

#El código está estructurado en varias secciones:

1. Importación de bibliotecas necesarias.
2. Obtención de datos de la API de Pokémon para crear la Tabla de Pokémon.
3. Definición de una clase para obtener información detallada de cada Pokémon.
4. Creación de la Tabla de Características combinando datos de Pokémon y fechas de lanzamiento de juegos.
5. Web scraping para obtener fechas de lanzamiento de juegos de Pokémon.
6. Funciones para combinar y procesar los datos obtenidos en las tablas finales.
7. Guardado de las tablas finales como archivos CSV para su posterior análisis.
   
El código está diseñado para ser ejecutado en un entorno como Google Colab, ya que incluye referencias a archivos y recursos específicos de ese entorno. Sin embargo, se puede adaptar para su ejecución en otros entornos.
