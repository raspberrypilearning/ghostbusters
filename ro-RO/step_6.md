## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

Cronometrul tău ar trebui:

+ Să înceapă în 10 secunde
+ Să numere înapoi fiecare secundă

Jocul ar trebui să se oprească când timpul ajunge la 0.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
când se dă click pe stegulețul verde
setează [timp v] la [10]
repetă până când < (timp) = [0] >
așteaptă (1) secunde
modifică [timp v] cu (-1)
end
stop [totul]
```

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---