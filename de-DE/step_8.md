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

\--- hints \--- \--- hint \--- `Wenn die grüne Flagge angeklickt wird`{:class=”block3events”}, sollte deine `Zeit`{:class=”block3variables”}-Variable `auf 10 gesetzt`{:class=”block3variables”} werden. Sie sollte dann jede Sekunde `um -1 geändert werden`{:class=”block3variables”} `bis sie den Wert 0 erreicht`{:class=”block3control"}. \--- /hint \--- \--- hint \--- Hier sind die Codeblöcke die du brauchst: ![Geist-Figur](images/ghost-backdrop.png)

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

\--- /hint \--- \--- hint \--- Hier ist der Code, den du hinzufügen solltest, um eine Stoppuhr zu erstellen: ![Hintergrund-Symbol](images/ghost-backdrop.png)

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

Bitte deine Freunde dein Spiel zu testen. Wie viele Punkte schaffen sie?

\--- /task \---

Wenn dein Spiel zu einfach ist, kannst du:

+ Dem Spieler weniger Zeit geben
+ die Gespenster weniger oft erscheinen lassen
+ die Gespenster kleiner machen

\--- task \---

Verändere und teste dein Spiel ein paar Mal, bis du mit dem Schwierigkeitsgrad zufrieden bist.

\--- /task \---