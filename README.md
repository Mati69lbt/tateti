# TA - TE - TI

![TA - TE - TI Logo](/src/assets/tateti.jpg)

TA - TE - TI es una aplicación web de entretenimiento que te permite disfrutar del clásico juego de tres en raya, también conocido como "Tres en línea". La aplicación ha sido desarrollada utilizando JavaScript, React y Vite, y está diseñada para ofrecer una experiencia de juego divertida y fácil de usar.

## Requisitos del sistema

Para ejecutar TA - TE - TI, se requiere lo siguiente:

- Un navegador web moderno con soporte para JavaScript.
- Conexión a Internet para cargar los recursos necesarios desde la web.

La aplicación ha sido optimizada para garantizar un rendimiento eficiente y una carga rápida, lo que permite que cualquier computadora con acceso a Internet pueda utilizarla sin problemas significativos. Incluso dispositivos más antiguos o con recursos limitados deberían ser capaces de ejecutarla sin dificultades.

## Instalación

No es necesario realizar ninguna instalación para utilizar TA - TE - TI, ya que se trata de una aplicación web. Simplemente accede al siguiente enlace: [TA - TE - TI](https://tatetilbt.netlify.app/) desde tu navegador preferido y podrás comenzar a jugar de inmediato.

## Estructura de directorios

El repositorio de la aplicación sigue la siguiente estructura de directorios:

- `src`: Directorio principal que contiene todo el código fuente de la aplicación.
  - `index.html`: Página HTML principal que carga la aplicación.
  - `components`: Carpeta que contiene los componentes de React utilizados en la aplicación.
    - `square.jsx`: Componente que representa una casilla del tablero de juego.
    - `winnerModal.jsx`: Componente que muestra el modal de victoria cuando un jugador gana.
  - `logic`: Carpeta que contiene los componentes lógicos de la aplicación.
    - `board.jsx`: Componente lógico que gestiona la lógica del juego y el estado del tablero.
    - `storage.jsx`: Componente lógico que maneja el almacenamiento de datos.

## Dependencias externas

TA - TE - TI utiliza la biblioteca `canvas-confetti` para generar efectos visuales cuando un jugador gana el juego. Esta dependencia se encarga de crear un efecto de confeti en la pantalla para celebrar la victoria. No se requiere ninguna acción adicional, ya que la biblioteca se carga automáticamente junto con la aplicación.

## Uso

1. Accede desde tu navegador web.
2. Haz clic en "Nuevo Juego" para comenzar una partida.
3. La partida se jugará por turnos entre dos jugadores. Uno utilizará una cruz roja y el otro una pelotita blanca.
4. Haz clic en una casilla vacía para colocar tu insignia (cruz o pelotita).
5. El objetivo es lograr que tres de tus insignias estén en línea recta (horizontal, vertical o diagonal).
6. Si un jugador consigue hacerlo, se mostrará un modal de victoria y se terminará el juego.
7. Para jugar otra partida, simplemente haz clic en "Nuevo Juego" nuevamente.
