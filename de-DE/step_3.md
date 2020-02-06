## Zufällige Gespenster

Dein Geist ist im Moment wirklich leicht zu fangen, weil er sich nicht bewegt!

\--- task \---

Kannst du deinem Geist Code hinzufügen, dass er nicht an der selben Stelle auf der Bühne bleibt, sondern an zufälligen Positionen auf der Bühne erscheint?

\--- hints \---

\--- hint \---

Jedes Mal, bevor dein Geist erscheint, sollte er zu einer zufälligen Position auf der Bühne `gehen`{:class="block3motion"}.

\--- /hint \--- \--- hint \---

Es gibt zwei Kombinationen von Codeblöcken, die du hier verwenden kannst. Suche dir die Kombination aus, die dir am besten gefällt.

![Geist-Figur](images/ghost-sprite.png)

Füge deiner Geister-Figur entweder diesen Block hinzu:

```blocks3
gehe zu (Zufallsposition v)
```

Oder füge diese Blöcke zu deiner Figur:

```blocks3
gehe nach x:(14) y:(50)

Zufallszahl von (1) bis (10)


Zufallszahl von (1) bis (10)
```

\--- /hint \---

\--- hint \---

Dein Code sollte entweder so aussehen:

![ghost-sprite](images/ghost-sprite.png)

```blocks3
Wenn die Flagge angeklickt wird
wiederhole fortlaufend
verstecke dich
warte (1) Sekunden
gehe zu (Zufallsposition v)
zeige dich
warte (1) Sekunden
ende
```

Oder er könnte so aussehen:

![ghost-sprite](images/ghost-sprite.png)

```blocks3
Wenn die Flagge angeklickt wird
wiederhole fortlaufend
verstecke dich
warte (1) Sekunden
gehe zu x:(Zufallszahl von (-150) bis (150)) y:(Zufallszahl von (-150) bis (150))
zeige dich
warte (1) Sekunden
ende
```

\--- /hint \--- \--- /hints \---

\--- /task \---