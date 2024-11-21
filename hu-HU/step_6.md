## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

Az időzítődnek:

+ 10 másodpercről kell indulnia
+ minden másodpercben vissza kell számolnia

A játéknak le kell állnia, ha az időzítő 0-hoz ér.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
⚑ -ra kattintáskor
[idő v] legyen [10]
ismételd eddig: < (time) = [0] >
várj (1) mp-et
[idő v] változzon (-1)
end
álljon le [minden feladat]
```

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---