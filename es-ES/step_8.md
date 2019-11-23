## Añadir un temporizador

Ahora vas a añadir un temporizador para que el jugador sólo tenga diez segundos para capturar tantos fantasmas como sea posible.

\--- task \---

Crea una nueva variable llamada 'tiempo'.

\--- /task \---

\--- task \---

¿Puedes añadir un temporizador a tu escenario para darle a tu jugador solo 10 segundos para atrapar fantasmas?

Tu temporizador debe:

+ Comenzar en 10 segundos
+ Contar hacia atrás cada segundo

El juego debería detenerse cuando el temporizador llegue a 0.

\--- hints \--- \--- hint \--- `Al hacer clic en la bandera verde`{:class=”block3events”}, tu variable `tiempo`{:class=”block3variables”} debería `tomar el valor 10`{:class=”block3variables"}. Después, se debe `sumar -1`{:class=”block3variables”} cada segundo `hasta que llegue a 0`{:class=”block3control"}. \--- /hint \--- \--- hint \--- Aquí están los bloques de código que necesitas usar: ![objeto fantasma](images/ghost-backdrop.png)

```blocks3
detener [all]

< [] = [] >

dar a [tiempo v] el valor [10]

sumar a [tiempo v] (-1)

(tiempo)

esperar (1) segundos

repetir hasta que < >
fin

al hacer clic en la bandera verde

```

\--- /hint \--- \--- hint \--- Aquí está el código que debes agregar para crear un temporizador: ![icono de fondo](images/ghost-backdrop.png)

```blocks3
al hacer clic en la bandera verde
dar a [tiempo v] el valor [10]
repetir hasta que < (tiempo) = [0]>
esperar (1) segundos
sumar a [tiempo v] (-1)
detener [all]
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

Cambia y prueba tu juego unas cuantas veces hasta que estés contento con su nivel de dificultad.

\--- /task \---