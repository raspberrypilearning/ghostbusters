## Eine Stoppuhr hinzufügen

Jetzt wirst du eine Stoppuhr hinzufügen, sodass die Spieler nur zehn Sekunden haben, um so viele Geister wie möglich zu fangen.

\--- task \---

Erstelle eine neue Variable und nenne sie "Zeit".

\--- /task \---

\--- task \---

Kannst du deiner Bühne eine Stoppuhr hinzufügen, um deinem Spieler nur 10 Sekunden Zeit zu geben, um so viele Geister wie möglich zu fangen?

Dein Timer sollte:

+ Bei 10 Sekunden beginnen
+ Jede Sekunde herunterzählen

Das Spiel soll aufhören, wenn der Timer auf 0 steht.

\--- hints \--- \--- hint \---

`When the green flag is clicked`{:class="block3events"}, your `time`{:class="block3variables"} variable should be `set to 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need to use:

![Geist-Figur](images/ghost-backdrop.png)

```blocks3
stoppe [alles]

<[ ] = [ ]>

setze [Zeit v] auf [10]

ändere [Zeit v] um (-1)

(Zeit)

warte (1) Sekunden

wiederhole bis < >
ende

Wenn die Flagge angeklickt wird

```

\--- /hint \--- \--- hint \---

Here is the code you should add to create a timer:

![Hintergrund-Symbol](images/ghost-backdrop.png)

```blocks3
Wenn die Flagge angeklickt wird
setze [Zeit v] auf [10]
wiederhole bis < (Zeit) = [0] >
warte (1) Sekunden
ändere [Zeit v] um (-1)
ende
stoppe [alles]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

If your game is too easy, you can:

+ Dem Spieler weniger Zeit geben
+ die Gespenster weniger oft erscheinen lassen
+ die Gespenster kleiner machen

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---