## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

Je timer zou moeten:

+ Beginnen met 10 seconden
+ Elke seconde aftellen

Het spel zou moeten stoppen als de timer op 0 komt.

\--- task \----

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \----

Add this code to your **Stage**:

![achtergrond pictogram](images/ghost-backdrop.png)

```blocks3
wanneer groene vlag wordt aangeklikt
maak [tijd v] [10]
herhaal tot < (tijd) = [0] >
wacht (1) sec.
verander [tijd v] met (-1)
end
stop [alle]
```

\--- /task \---

\--- task \----

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \----

Verander en test je spel een paar keer totdat je tevreden bent met de moeilijkheidsgraad.

\--- /task \---