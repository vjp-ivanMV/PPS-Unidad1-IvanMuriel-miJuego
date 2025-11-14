# 🏁 Carrera a la Meta (Juego de Tablero CLI)

`Carrera a la Meta` es un sencillo juego de tablero multijugador (3 jugadores) implementado en Python para la línea de comandos. El objetivo es ser el primer jugador en llegar a la casilla 24 ("Meta"), ¡pero cuidado con que no te "coman" en el camino!

## 🚀 Características

* **Multijugador (Local):** Diseñado para 3 jugadores en el mismo ordenador.
* **Tablero Interactivo:** Muestra las posiciones de todos los jugadores en la consola después de cada turno.
* **Sistema de "Comer":** Si un jugador cae en la misma casilla que otro, el jugador que estaba allí es enviado de vuelta al "Inicio".
* **Inicio Aleatorio:** El jugador que empieza se decide por sorteo al comenzar la partida.
* **Interfaz Sencilla:** Controlado completamente por la terminal pulsando "Enter".

## 🎮 Cómo Jugar

1.  Inicia el juego. Cada uno de los 3 jugadores debe introducir una **inicial única** (letra mayúscula) para identificarse.
2.  El juego sorteará quién empieza.
3.  Por turnos, cada jugador pulsará "Enter" para tirar un dado (del 1 al 6).
4.  El jugador avanzará el número de casillas indicado por el dado.
5.  **¡Regla Especial!** Si caes en una casilla (que no sea "Inicio") donde ya hay otro jugador, ese jugador es "comido" y debe **regresar a la casilla 0 ("Inicio")**.
6.  **¡Victoria!** El primer jugador que llegue o supere la casilla 24 ("Meta") gana la partida inmediatamente.

## 💻 Requisitos

* **Python 3.x**

No se requieren bibliotecas externas, ya que el juego solo utiliza los módulos `random` y `time` (incluidos en la biblioteca estándar de Python).

## 🏃 Cómo Ejecutar

1.  Asegúrate de tener Python 3 instalado.
2.  Clona este repositorio o descarga el archivo `.py` (por ejemplo, `juego.py`).
3.  Abre una terminal o línea de comandos.
4.  Navega hasta el directorio donde guardaste el archivo.
5.  Ejecuta el siguiente comando:

```bash
python juego.py
