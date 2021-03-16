# Music Player React

Vamos a crear un reproductor de MP3 que funciona de manera similar a Spotify, ![Todo List](https://github.com/breatheco-de/exercise-music-player-react/blob/master/preview.gif?raw=true).

- Los botones siempre deben permanecer en la parte inferior de la ventana gráfica o viewport (usa la posición fija para eso).
- Solo tienes que implementar los botones Reproducir, Pausa, Siguiente y anterior.

## 🌱  Cómo empezar este proyecto

Este proyecto viene con los archivos necesarios para trabajar, pero puedes empezar de dos formas:

a) Use gitpod: open this link in your browser to clone it with gitpod: https://gitpod.io#https://github.com/breatheco-de/exercise-music-player-react.git

b) You can clone this repository on your local computer:
```sh
$ git clone https://github.com/breatheco-de/exercise-music-player-react.git
```

## 📝 Requisitos:

- Listar las canciones de [esta API](http://assets.breatheco.de/apis/sound/)utilizando la Fetch API,
- Cuando el usuario hace clic en una canción, el player (reproductor) debe comenzar a reproducirla.
- Cuando el usuario hace clic en el botón "siguiente", el reproductor debe comenzar a reproducir la siguiente canción de la lista, si no hay una canción siguiente, debe comenzar     nuevamente a reproducir la primera canción de la lista, lo mismo aplica para el botón "anterior".
- Usa el atributo reaccionar ref de react para obtener la etiqueta o tag de audio del DOM.
- Asegurate de que haya una sola etiqueta o tag `<audio>` en todo el proyecto, usa `ref`para cambiar su src url.

## Recomendaciones
- Usa la funcion `useRef`.
- No llames a la función setState porque perderá el estado de la etiqueta de audio si se llama a la función de render

## 😎 Te sientes con confianza?

Los siguientes requerimientos no son necesarios para entregar la solucion pero puedes intentar realizarlos si tienes tiempo y te sientes con confianza.

+1 Implementa control de volumen": dos botones, uno para subir y otro para bajar el volumen.
+1 Modo repeticion: un checkbox que cuando esta activo, la cancion se repetirá eternamente.
+2 Aleatorio:: un botón que al presionarlo reproduzca una canción aleatoriamente.
+5 Medidor de progreso de la canción: Implementa un slider o progress bar que se complete a medida que la cancion se reproduce.
