## Agregar un temporizador

Ahora vas a agregar un temporizador para que el jugador solo tenga diez segundos para capturar tantos fantasmas como sea posible.

\--- task \---

Crea una nueva variable llamada 'tiempo'.

\--- /task \---

\--- task \---

¿Puedes añadir un temporizador a tu escenario para darle a tu jugador solo 10 segundos para atrapar tantos fantasmas como sea posible?

Tu temporizador debería:

+ Comenzar en 10 segundos
+ Contar para atrás cada segundo

El juego debería detenerse cuando el temporizador llegue a 0.

\--- hints \--- \--- hint \---

`When the green flag is clicked`{:class="block3events"}, your `time`{:class="block3variables"} variable should be `set to 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need to use:

![sprite fantasma](images/ghost-backdrop.png)

```blocks3
detener [todos]

< [] = [] >

dar a [tiempo v] el valor [10]

sumar a [tiempo v] (-1)

(tiempo)

esperar (1) segundos

repetir hasta < >

al hacer clic en la bandera

```

\--- /hint \--- \--- hint \---

Here is the code you should add to create a timer:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
al hacer clic en la bandera
dar a [tiempo v] el valor [10]
repetir hasta que < (tiempo) = [0] >
esperar (1) segundos
sumar a [tiempo v] (-1)
detener [todos]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

If your game is too easy, you can:

+ Darle menos tiempo al jugador
+ Hacer que los fantasmas aparezcan con menos frecuencia
+ Hacer los fantasmas más pequeños

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---