## Adicionar um cronômetro

Agora você vai adicionar um cronômetro de forma que o jogador tenha apenas dez segundos para pegar o maior número possível de fantasmas.

\--- task \---

Crie uma nova variável chamada 'tempo'.

\--- /task \---

\--- task \---

Será que você consegue adicionar um cronômetro no seu Palco para dar ao seu jogador somente 10 segundos para capturar fantasmas?

Seu cronômetro deve:

+ Começar mostrando 10 segundos
+ Contagem regressiva a cada segundo

O jogo deve parar quando o cronômetro chegar a 0.

\--- hints \--- \--- hint \---

`When the green flag is clicked`{:class="block3events"}, your `time`{:class="block3variables"} variable should be `set to 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need to use:

![ator do fantasma](images/ghost-backdrop.png)

```blocks3
pare [todos]

< [ ] = [ ] >

mude [tempo v] para [10]

adicione (-1) a [tempo v]

(tempo)

espere (1) seg

repita até que < >
fim

quando badeira verde for clicado

```

\--- /hint \--- \--- hint \---

Here is the code you should add to create a timer:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
quando bandeira verde for clicada
mude [tempo v] para [10]
repita até que < (tempo) = [0] >
espere (1) segundo
adicione (-1) a [tempo v]
fim
pare [todos]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

If your game is too easy, you can:

+ Dar ao jogador menos tempo
+ Fazer os fantasmas aparecerem com menos frequência
+ Diminuir o tamanho dos fantasmas

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---