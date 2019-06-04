# Music Player React

<<<<<<< HEAD
Vamos a crear un reproductor de MP3 que funciona de manera similar a Spotify, [aqui esta la demo](https://projects.breatheco.de/json/?slug=music-player-react&preview/).
=======
<p align="center"><img height="300" src="https://projects.breatheco.de/json?slug=music-player-react&preview" /></p>

Let's create a MP3 player that works similar to Spotify, [here is the demo](https://projects.breatheco.de/json?slug=music-player-react&preview).
>>>>>>> 2c44ba329b8aa6dc38c7c6988cf83d429581a525

Los botones siempre deben permanecer en la parte inferior de la ventana gráfica (use la posición fijada para eso).
Solo necesita implementar los botones Reproducir, Pausa, Siguiente y anterior.

<<<<<<< HEAD

## Requerimientos
- Listar las canciones de [esta API](http://assets.breatheco.de/apis/sound/)utilizando la función de fetch.
- Cuando el usuario hace clic en una canción, el jugador debe comenzar a reproducirla.
- Cuando el usuario hace clic en el botón "siguiente", el reproductor debe comenzar a reproducir la siguiente canción de la lista, si no hay una canción siguiente, debe comenzar nuevamente tocando la primera canción de la lista, lo mismo se aplica a la "anterior" botón.
- Use el atributo reaccionar ref para obtener la etiqueta de audio del DOM.
- No hay necesidad de volumen.

## Recomendaciones
- Nunca llame a la función setState porque perderá el estado de la etiqueta de audio si se llama a la función de render.
=======
## Requierments
- List the songs from [the Sounds API](http://assets.breatheco.de/apis/sound/) using the Fetch API.
- When the user clicks on a song, the player it must start playing it.
- When the user clicks on the "next" button the player should start playing the next song from the list, if there is no next song then it should start over by playing the first song of the list, the same applies for the "previous" button.
- Use the react ref attribute to get the audio tag from the DOM.
- There is not need for volume but you can implement the function if you feel confidente enough.
>>>>>>> 2c44ba329b8aa6dc38c7c6988cf83d429581a525
