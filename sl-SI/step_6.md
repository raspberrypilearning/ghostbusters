## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

Tvoj časovnik mora:

+ Začeti pri 10 sekund
+ Odštevati po eno skundo

Igra se mora ustaviti, ko časovnik doseže 0.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
ko kliknemo na zastavico
nastavi [čas V] na [10]
ponavljaj do < (čas) = [0] >
počakaj (1) sekund
spremeni [čas V] za (-1)
konec
ustavi [vse]
```

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

Spreminjaj in preizkušaj svojo igro, dokler nisi zadovoljen z njeno težavnosto stopnjo.

\--- /task \---