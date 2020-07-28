## Añade una puntuación

¡Ahora vas a hacer que tu juego sea más interesante añadiendo un sistema de puntuación!

--- task ---

Crea una nueva variable llamada `marcador`{:class="block3variables"}.

[[[generic-scratch3-add-variable]]]

--- /task ---

--- task ---

¿Puedes llevar la cuenta de la puntuación del jugador? Los jugadores deberían ganar puntos haciendo clic en los fantasmas para atraparlos.

Cada vez que un jugador hace clic en un fantasma, su puntuación debe aumentar.

![Incrementar la puntuación](images/ghost-score-test.png)

--- hints ---
 --- hint ---

`Al hacer clic en la bandera verde`{:class="block3events"}, debes dar a tu variable `marcador`{:class="block3data"} `el valor 0`{:class="block3data"}. El escenario es el mejor lugar para añadir este código.

`Al hacer clic en el fantasma`{:class="block3events"}, deberías `sumar 1`{:class="block3data"} a la variable `marcador`{:class="block3data"}.

--- /hint --- --- hint ---

Aquí están los bloques de código que necesitas:

![icono de fondo](images/ghost-backdrop.png)

```blocks3
set [marcador v] to (0)

when flag clicked
```

![sprite fantasma](images/ghost-sprite.png)

```blocks3
change [marcador v] by (1)
```

--- /hint --- --- hint ---

![icono de fondo](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [marcador v] to (0)
```

![objeto fantasma](images/ghost-sprite.png)

```blocks3
When this sprite clicked
hide
+ change [marcador v] by (1)
```

--- /hint ------ /hints ---

--- /task ---