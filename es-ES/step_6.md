## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

Tu temporizador debe:

+ Comenzar en 10 segundos
+ Contar hacia atrás cada segundo

El juego debería detenerse cuando el temporizador llegue a 0.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
al hacer clic en la bandera verde
dar a [tiempo v] el valor [10]
repetir hasta que < (tiempo) = [0]>
esperar (1) segundos
sumar a [tiempo v] (-1)
detener [all]
```

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---