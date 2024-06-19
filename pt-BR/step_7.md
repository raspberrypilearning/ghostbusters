## Adicionar uma pontuação

Agora você vai tornar seu jogo mais interessante marcando a pontuação!

--- task ---

Crie uma nova variável chamada de `pontuação`{:class="block3variables"}.

[[[generic-scratch3-add-variable]]]

--- /task ---

--- task ---

Você consegue acompanhar a pontuação do jogador? Os jogadores marcam pontos ao clicar nos fantasmas para capturá-los.

Cada vez que um jogador clicar em um fantasma, sua pontuação deve aumentar.

![Aumentando a pontuação](images/ghost-score-test.png)

--- hints ---
 --- hint ---

`Quando bandeira verde for clicada`{:class="block3events"}, sua variável da `pontuação`{:class="block3variables"} deve `mudar para 0`{:class="block3variables"}. O Palco é o melhor lugar para adicionar esse código.

`Quando o fantasma for clicado`{:class="block3events"}, a variável da `pontuação`{:class="block3variables"} `deverá ser somada em 1`{:class="block3variables"}.

--- /hint --- --- hint --- Aqui estão os blocos de código que você precisa: ![backdrop icon](images/ghost-backdrop.png)

```blocks3
set [pontuação v] to (0)

when flag clicked
```

![Objeto gráfico fantasma](images/ghost-sprite.png)

```blocks3
change [pontuação v] by (1)
```

--- /hint --- --- hint ---

![Ícone de fundo](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [pontuação v] to (0)
```

![Objeto gráfico fantasma](images/ghost-sprite.png)

```blocks3
When this sprite clicked
hide
+ change [pontuação v] by (1)
```

--- /hint ------ /hints ---

--- /task ---