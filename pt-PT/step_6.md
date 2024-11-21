## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

O teu cronómetro deve:

+ Iniciar com 10 segundos
+ Contar de forma regressiva todos os segundos

O jogo deve parar quando o cronómetro chegar a 0.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

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

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

Muda e testa o teu jogo algumas vezes até ficares satisfeito com o nível de dificuldade.

\--- /task \---