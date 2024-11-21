## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

Il tuo timer dovrebbe:

+ Partire da 10 secondi
+ Contare alla rovescia ogni secondo

Il gioco dovrebbe interrompersi quando il timer raggiunge lo 0.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

![icona scenario](images/ghost-backdrop.png)

```blocks3
quando si clicca sulla bandiera verde
porta [time v] a [10]
ripeti fino a quando <(time) = [0]>
attendi (1) secondi
cambia [time v] di (-1)
end
ferma [all]
```

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

Cambia e prova il tuo gioco alcune volte fino a quando non sei soddisfatto del suo livello di difficoltà.

\--- /task \---