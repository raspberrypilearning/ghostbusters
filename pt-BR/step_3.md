## Fantasmas aleatórios

Seu fantasma é realmente fácil de pegar no momento já que ele não se move!

--- task ---

Será que você consegue adicionar código ao seu fantasma assim, em vez de ficar na mesma posição, o fantasma apareça em posições aleatórias no Palco?

--- hints ---


--- hint ---

Cada vez que seu fantasma aparecer, ele deverá `ir para`{:class="block3motion"} uma posição aleatória no Palco.

--- /hint --- --- hint ---

Há dois conjuntos de blocos de código que você pode usar aqui. Escolha o conjunto que você preferir.

![ator do fantasma](images/ghost-sprite.png)

Ou adicione este conjunto de blocos ao seu fantasma:

```blocks3
ir para (posição aleatória v)
```

Ou adicione este a seu fantasma:

```blocks3
ir para x: (14) y: (50)

(número aleatório entre (1) e (10))

(número aleatório entre (1) e (10))
```

--- /hint ---

--- hint ---

Seu código deve ficar assim:

![ator do fantasma](images/ghost-sprite.png)

```blocks3
quando ⚑ for clicado
para sempre
ocultar
esperar (1) segundos
vá para(posição aleatória v)
mostrar
esperar (1) segundos
fim
```

Ou poderia ser assim:

![ator do fantasma](images/ghost-sprite.png)

```blocks3
quando ⚑ for clicado
para sempre
ocultar
esperar (1) segundos
vá para x: (número aleatório entre (-150) e (150)) y: (número aleatório entre (-150) e (150))
mostrar
esperar (1) segundos
fim
```

--- /hint ------ /hints ---

--- /task ---