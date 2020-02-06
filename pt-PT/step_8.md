## Adiciona um cronómetro

Agora vais adicionar um cronómetro de formam a que o jogador tenha apenas dez segundos para capturar o maior número possível de fantasmas.

\--- task \---

Cria uma nova variável chamada 'tempo'.

\--- /task \---

\--- task \---

Consegues adicionar um cronómetro ao teu Palco para dar ao teu jogador apenas 10 segundos para capturar fantasmas?

O teu cronómetro deve:

+ Iniciar com 10 segundos
+ Contar de forma regressiva todos os segundos

O jogo deve parar quando o cronómetro chegar a 0.

\--- hints \--- \--- hint \---

`When the green flag is clicked`{:class="block3events"}, your `time`{:class="block3variables"} variable should be `set to 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need to use:

![ghost-sprite](images/ghost-backdrop.png)

```blocks3
pára [all]

<[ ] = [ ]>

altera [time v] para [10]

adiciona a [time v] o valor (-1)

(time)

espera (1) s

até que < > , repete
end

Quando alguém clicar na bandeira verde

```

\--- /hint \--- \--- hint \---

Here is the code you should add to create a timer:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
quando alguém clicar na bandeira verde
altera [time v] para [10]
até que <(time) = [0]>, repete 
 espera (1) s
 adiciona a [time v] o valor (-1)
end
pára [all]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

If your game is too easy, you can:

+ Dá menos tempo ao jogador
+ Faz com que os fantasmas apareçam com menos frequência
+ Faz os fantasmas mais pequenos

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---