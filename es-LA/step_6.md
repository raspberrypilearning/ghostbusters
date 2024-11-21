## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

Tu temporizador debería:

+ Comenzar en 10 segundos
+ Contar para atrás cada segundo

El juego debería detenerse cuando el temporizador llegue a 0.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

![icono de fondo](images/ghost-backdrop.png)

```blocks3
al hacer clic en la bandera
dar a [tiempo v] el valor [10]
repetir hasta que < (tiempo) = [0] >
esperar (1) segundos
sumar a [tiempo v] (-1)
detener [todos]
```

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

Modifica y prueba tu juego varias veces hasta que creas que tiene el nivel de dificultad adecuado.

\--- /task \---