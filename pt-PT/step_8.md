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

` Quando a bandeira verde é clicada ` {: class = "block3events"}, a tua variável ` tempo ` {: class = "block3variables"} deve ser ` alterada para 10 ` {: class = "block3variables"}. Deve então ` mudar em -1 ` {: class = "block3variables"} a cada segundo ` até chegar a 0 ` {: class = "block3control"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need to use:

![ator fantasma](images/ghost-backdrop.png)

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

![ícone de fundo](images/ghost-backdrop.png)

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

Pede a um amigo para testar o teu jogo. Quantos pontos conseguem eles fazer?

\--- /task \---

Se o teu jogo é muito fácil, podes:

+ Dá menos tempo ao jogador
+ Faz com que os fantasmas apareçam com menos frequência
+ Faz os fantasmas mais pequenos

\--- task \---

Muda e testa o teu jogo algumas vezes até ficares satisfeito com o nível de dificuldade.

\--- /task \---