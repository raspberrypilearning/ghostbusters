## Adiciona uma pontuação

Agora vais tornar o teu jogo mais interessante, guardando a pontuação!

\--- task \---

Cria uma nova variável chamada `pontuação`{:class="block3variables"}.

[[[generic-scratch3-add-variable]]]

\--- /task \---

\--- task \---

Consegues guardar a pontuação do jogador? Os jogadores devem marcar pontos quando clicarem em fantasmas para os apanhar.

De cada vez que um jogador clicar num fantasma, a sua pontuação deve aumentar.

![Pontuação crescente](images/ghost-score-test.png)

\--- hints \--- \--- hint \---

` Quando a bandeira verde é clicada ` {: class = "block3events"}, a tua variável ` pontuação ` {: class = "block3variables"} deve ser ` alterada para 0 ` {: class = "block3variables"}. O palco é o melhor lugar para colocar esse código.

` Quando a bandeira verde é clicada ` {: class = "block3events"}, a variável ` pontuação ` {: class = "block3variables"} deve ser ` alterada em 1 ` {: class = "block3variables"}.

\--- /hint \--- \--- hint \---

Estes são os blocos de que necessitas:

![ícone de fundo](images/ghost-backdrop.png)

```blocks3
altera [score v] para (0)

quando alguém clicar na bandeira verde
```

![ator fantasma](images/ghost-sprite.png)

```blocks3
adiciona a [score v] o valor (1)
```

\--- /hint \--- \--- hint \---

![ícone de fundo](images/ghost-backdrop.png)

```blocks3
quando alguém clicar na bandeira verde
altera [score v] para (0)
```

![ator fantasma](images/ghost-sprite.png)

```blocks3
Quando alguém clicar em ti
esconde-te

+adiciona a [score v] o valor (1)
```

\--- /hint \--- \--- /hints \---

\--- /task \---