# Objetivo
¡Bienvenido a DDcampeonato de fútbol!. En esta actividad deberás **organizar las próximas fechas del campeonato de fútbol, asegurando que cada equipo se enfrente al menos una vez entre sí**.

# Desarrollo de la actividad
Para lograr esta tarea, deberás crear la función **obtener_próximos**, la cual recibe 2 parámetros. El primer parámetro es **partidos**, una lista de listas, donde cada elemento de la lista representa un partido ya jugado. A su vez, cada partido está compuesto por los nombres de los 2 equipos que se enfrentaron. Siguiendo el siguiente formato de ejemplo:

partidos = [
    ["nombre1", "nombre2"], 
    ["nombre3", "nombre1"]
]

El segundo parámetro que deberás recibir es **equipo**, un str que representa el nombre del equipo para el cual deberás encontrar sus rivales pendientes.

Con estos parametros deberás crear la lógica de la función que finalmente deberá devolver una lista que contenga los nombres de los próximos rivales.

# Consideraciones 
+ La lista de partidos jugados puede estar vacía.
+ Puedes asumir que no existirá más de un equipo con el mismo nombre.


# Ejemplo 
En tu DCCampeonato se han inscrito 4 equipos, cuyos nombres son platano, manzana, pera y uva. Adicionalmente se te pide encontrar los próximos rivales del equipo plátano y para ello se te entrega la siguiente lista:

partidos = [
    ["platano", "manzana"], 
    ["pera", "uva"],
    ["uva", "platano"],
    ["manzana", "pera"],
]

Observando la lista vemos que este equipo ya se ha enfrentado a manzana y uva, por ende, ha jugado con 2 de los 3 rivales inscritos y el único pendiente es pera, por ende se espera que tu función retorne [`pera`] como resultado.
