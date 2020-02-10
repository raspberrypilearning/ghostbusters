## Fantasmas aleatórios

O teu fantasma é realmente fácil de apanhar neste momento, porque não se move!

\--- task \---

Consegues adicionar código ao seu fantasma para que, em vez de permanecer na mesma posição, o apareça em posições aleatórias no Palco?

\--- hints \---

\--- hint \---

Sempre que o teu fantasma aparecer, ele deve ` ir para ` {: class = "block3motion"} uma posição aleatória no palco.

\--- /hint \--- \--- hint \---

Existem dois conjuntos de blocos de código que podes utilizar aqui. Escolhe o conjunto que preferires.

![ator fantasma](images/ghost-sprite.png)

Adiciona este conjunto de blocos ao teu sprite fantasma:

```blocks3
vai para (random position v)
```

Ou adiciona este ao seu sprite:

```blocks3
vai para a posição x: (14) y: (50)

um valor ao acaso entre (1) e (10)

um valor ao acaso entre (1) e (10)
```

\--- /hint \---

\--- hint \---

O teu código deverá ter este aspeto:

![ator fantasma](images/ghost-sprite.png)

```blocks3
quando alguém clicar na bandeira verde
repete para sempre 
esconde-te
espera (1) s
vai para (random position v)
mostra-te
espera (1) s
end
```

O teu código deverá ter este aspeto:

![ator fantasma](images/ghost-sprite.png)

```blocks3
quando alguém clicar na bandeira verde
repete para sempre 
esconde-te
espera (1) s
vai para a posição x: (um valor ao acaso entre (-150) e (150)) y: (um valor ao acaso entre (-150) e (150))
mostra-te
espera (1) s
end
```

\--- /hint \--- \--- /hints \---

\--- /task \---