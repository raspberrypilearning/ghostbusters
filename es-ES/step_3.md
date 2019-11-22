## Fantasmas aleatorios

¡Tu fantasma es muy fácil de atrapar en este momento, porque no se mueve!

\--- task \---

¿Puedes agregar código a tu fantasma para que, en lugar de permanecer en la misma posición, el fantasma aparezca en posiciones aleatorias en el escenario?

\--- hints \---

\--- hint \---

Cada vez que tu fantasma aparezca, debería `ir a` {:class="block3motion"} una posición aleatoria en el escenario.

\--- /hint \--- \--- hint \---

Hay dos conjuntos de bloques de código que puedes usar aquí. Elige el conjunto que prefieras.

![objeto fantasma](images/ghost-sprite.png)

Puedes agregar este conjunto de bloques a tu fantasma:

```blocks3
ir a (posición aleatoria v)
```

O agregar este a tu objeto:

```blocks3
ir a x: (14) y: (50)

número aleatorio entre (1) y (10)

número aleatorio entre (1) y (10)
```

\--- /hint \---

\--- hint \---

Tu código podría verse así:

![objeto fantasma](images/ghost-sprite.png)

```blocks3
al hacer clic en la bandera
por siempre
esconder
esperar (1) segundos
ir a (posición aleatoria v)
mostrar
esperar (1) segundos
fin
```

O podría verse así:

![objeto fantasma](images/ghost-sprite.png)

```blocks3
al hacer clic en la bandera
por siempre
esconder
esperar (1) segundos
ir a x: (número aleatorio entre (-150) y (150)) y: (número aleatorio entre (-150) y (150))
mostrar
esperar (1) segundos
fin
```

\--- /hint \--- \--- /hints \---

\--- /task \---