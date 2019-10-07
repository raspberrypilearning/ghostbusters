## Fantasmas aleatorios

¡Tu fantasma es muy fácil de atrapar en este momento, porque no se mueve!

\--- task \---

¿Puedes agregar código a tu fantasma para que, en lugar de permanecer en la misma posición, aparezca en posiciones aleatorias en la pantalla?

\--- hints \---

\--- hint \---

Cada vez que aparezca tu fantasma, debería `ir a`{:class="block3motion"} una posición aleatoria en el Escenario.

\--- /hint \--- \--- hint \---

Hay dos conjuntos de bloques de código que puedes usar aquí. Elige el conjunto que prefieras.

![sprite fantasma](images/ghost-sprite.png)

Añade este conjunto de bloques a tu sprite fantasma:

```blocks3
ir a (posición aleatoria v)
```

O añade este a tu sprite:

```blocks3
ir a x: (14) y: (50)

número aleatorio entre (1) y (10)

número aleatorio entre (1) y (10)
```

\--- /hint \---

\--- hint \---

Tu código debería verse así:

![sprite fantasma](images/ghost-sprite.png)

```blocks3
al hacer clic en bandera verde
por siempre
esconder
esperar (1) segundos
ir a (posición aleatoria v)
mostrar
esperar (1) segundos
```

O podría parecerse a esto:

![sprite fantasma](images/ghost-sprite.png)

```blocks3
al hacer clic en bandera verde
por siempre
esconder
esperar (1) segundos
ir a x: (número aleatorio entre (1) y (10)) y: (número aleatorio entre (1) y (10))
mostrar
esperar (1) segundos
```

\--- /hint \--- \--- /hints \---

\--- /task \---