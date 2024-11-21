## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

Twój licznik czasu powinien:

+ Zacząć od 10 sekund
+ Odliczać co sekundę

Gra powinna się zatrzymać, gdy czas dojdzie do 0.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
kiedy flaga kliknięta
ustaw [czas v] na [10]
powtarzaj, aż < (czas) = [0] >
czekaj (1) sekund
zmiań [czas v] o (-1)
koniec
zatrzymaj [all]
```

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---