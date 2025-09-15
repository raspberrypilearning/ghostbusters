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
go to (posição aleatória v)
```

Ou adicione este a seu fantasma:

```blocks3
go to x: (14) y: (50)

pick random (1) to (10)

pick random (1) to (10)
```

--- /hint ---

--- hint ---

Seu código deve ficar assim:

![ator do fantasma](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to (posição aleatória v)
show
wait (1) seconds
end
```

Ou poderia ser assim:

![ator do fantasma](images/ghost-sprite.png)

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