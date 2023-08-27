# Pokemons
Para este proyecto se va ha hacer una versión de uno de los videojuegos más famosos de la historia: Pokémon. Tendrás que usar todas tus habilidades de Pythonista creando clases, instancias, métodos, condicionales y ciclos para lograr tu meta.

# ¿Cómo lo haremos?
Crea una clase Pokemon que tenga como atributos su especie, tipo, fortalezas, debilidades y estadísticas de ataque, defensa, velocidad y puntos de vida.
Implementa el método combate que tome como argumento un rival (otra instancia de la clase Pokemon). El combate va a ser como el de los videojuegos, por lo que va a ser por turnos en los que cada turno cada pokemon realiza un ataque que resta puntos de vida del rival hasta. Este se detiene cuando los puntos de vida de alguno de los dos llegue a cero. Asegúrate que cumpla lo siguiente:
i. El Pokémon de mayor velocidad es el que ataca primero.
ii. Si alguien es atacado por una de sus debilidades, recibe el doble de daño. Si es atacado por una de sus fortalezas, recibe sólo la mitad de daño.
iii. Calcula el daño y réstalos de los puntos de vida.
iv. En cuanto uno tenga 0 puntos de vida, termina el ciclo y declara un ganador
Crea un método llamado centro_pokemon para regresar los puntos de vida a sus valores originales.
Implementa el que los jugadores puedan elegir distintos movimientos, estos deben de tener distinta capacidad de daño y distinto tipo.
Modifica el cálculo de daño para que el multiplicador de fortaleza/debilidad se calcule con el tipo del movimiento (no del tipo del atacante) y las debilidades/fortalezas del pokemon que defiende.
Usa lo que aprendiste de las herencias para mejorar tu programa. Crea clases PokemonAgua, PokemonFuego y PokemonPlanta que hereden de la clase Pokémon y que determinen los tipos, fortalezas y debilidades correspondientes.
Crea clases que hereden de las que creaste el punto anterior: Squirtle, Charmander y Bulbasaur. Que contengan la información de las estadísticas de especie, y estadísticas de ataque, defensa, velocidad y puntos de vida.
