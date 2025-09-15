## Fantasmas aleatorios

¡Tu fantasma es muy fácil de atrapar en este momento, porque no se mueve!

--- task ---

¿Puedes agregar código a tu fantasma para que, en lugar de permanecer en la misma posición, aparezca en posiciones aleatorias en la pantalla?

--- hints ---


--- hint ---

Cada vez que aparezca tu fantasma, debería `ir a`{:class="block3motion"} una posición aleatoria en el Escenario.

--- /hint --- --- hint ---

Hay dos conjuntos de bloques de código que puedes usar aquí. Elige el conjunto que prefieras.

![sprite fantasma](images/ghost-sprite.png)

Añade este conjunto de bloques a tu sprite fantasma:

```blocks3
go to (random position v)
```

O añade este a tu sprite:

```blocks3
go to x: (14) y: (50)

pick random (1) to (10)

pick random (1) to (10)
```

--- /hint ---

--- hint ---

Tu código debería verse así:

![sprite fantasma](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to (random position v)
show
wait (1) seconds
end
```

O podría parecerse a esto:

![sprite fantasma](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to x: (pick random (-150) to (150)) y: (pick random (-150) to (150))
show
wait (1) seconds
end
```

--- /hint ------ /hints ---

--- /task ---