## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

Dein Timer sollte:

+ Bei 10 Sekunden beginnen
+ Jede Sekunde herunterzählen

Das Spiel soll aufhören, wenn der Timer auf 0 steht.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
Wenn die Flagge angeklickt wird
setze [Zeit v] auf [10]
wiederhole bis < (Zeit) = [0] >
warte (1) Sekunden
ändere [Zeit v] um (-1)
ende
stoppe [alles]
```

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---