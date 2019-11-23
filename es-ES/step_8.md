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
stop [all]

< [ ] = [ ] >

set [time v] to [10]

change [time v] by (-1)

(time)

wait (1) seconds

repeat until < >
end

when flag clicked

```

\--- /hint \--- \--- hint \--- Here is the code you should add to create a timer: ![icono de fondo](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [time v] to [10]
repeat until < (time) = [0] >
wait (1) seconds
change [time v] by (-1)
end
stop [all]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

Si tu juego es demasiado fácil, puedes:

+ Darle menos tiempo al jugador
+ Hacer que los fantasmas aparezcan con menos frecuencia
+ Hacer los fantasmas más pequeños

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---