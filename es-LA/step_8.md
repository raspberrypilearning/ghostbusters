## Agregar un temporizador

Ahora vas a agregar un temporizador para que el jugador solo tenga diez segundos para capturar tantos fantasmas como sea posible.

--- task ---

Crea una nueva variable llamada 'tiempo'.

--- /task ---

--- task ---

¿Puedes añadir un temporizador a tu escenario para darle a tu jugador solo 10 segundos para atrapar tantos fantasmas como sea posible?

Tu temporizador debería:

+ Comenzar en 10 segundos
+ Contar para atrás cada segundo

El juego debería detenerse cuando el temporizador llegue a 0.

--- hints ---
 --- hint ---

`Al hacer clic en la bandera verde`{:class="block3events"}, debes dar a tu variable `marcador`{:class="block3variables"} `el valor 10`{:class="block3variables"}. Después, se deberías `sumar -1`{:class="block3variables"} cada segundo `hasta que llegue a 0`{:class="block3control"}.

--- /hint --- --- hint ---

Aquí están los bloques de código que necesitas:

![objeto fantasma](images/ghost-backdrop.png)

```blocks3
stop [all]

< [ ] = [ ] >

set [tiempo v] to [10]

change [tiempo v] by (-1)

(tiempo)

wait (1) seconds

repeat until < >
end

when flag clicked

```

--- /hint --- --- hint ---

Aquí esta el código que debes agregar para crear un temporizador:

![icono de fondo](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [tiempo v] to [10]
repeat until < (tiempo) = [0] >
wait (1) seconds
change [tiempo v] by (-1)
end
stop [all]
```

--- /hint ------ /hints ---

--- /task ---

--- task ---

Pídele a un amigo que pruebe tu juego. ¿Cuántos puntos pueden anotar?

--- /task ---

Si tu juego es demasiado fácil, puedes:

+ Darle menos tiempo al jugador
+ Hacer que los fantasmas aparezcan con menos frecuencia
+ Hacer los fantasmas más pequeños

--- task ---

Modifica y prueba tu juego varias veces hasta que creas que tiene el nivel de dificultad adecuado.

--- /task ---