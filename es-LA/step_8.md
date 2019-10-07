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

\--- hints \--- \--- hint \--- `Al hacer clic en la bandera verde`{:class=”blockevents”}, debes `dar el valor 10`{:class=”blockdata"} a tu variable `tiempo`{:class=”blockdata”}. Después, se deberías `sumar -1`{:class=”blockdata”} cada segundo `hasta que llegue a 0`{:class=”blockcontrol"}. \--- /hint \--- \--- hint \--- Los bloques de código que necesitará se encuentran a continuación: ![sprite fantasma](images/ghost-backdrop.png)

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

\--- /hint \--- \--- hint \--- Aquí está el código que debes agregar para crear un temporizador: ![icono de fondo](images/ghost-backdrop.png)

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

Pídele a un amigo que pruebe tu juego. ¿Cuántos puntos pueden anotar?

\--- /task \---

Si tu juego es demasiado fácil, puedes:

+ Darle menos tiempo al jugador
+ Hacer que los fantasmas aparezcan con menos frecuencia
+ Hacer los fantasmas más pequeños

\--- task \---

Modifica y prueba tu juego varias veces hasta que creas que tiene el nivel de dificultad adecuado.

\--- /task \---