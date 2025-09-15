## Eine Punktzahl hinzufügen

Jetzt wirst du dein Spiel interessanter machen, indem du Punkte sammelst!

--- task ---

Erstelle eine neue Variable namens `Punkte`{:class="block3variable"}.

[[[generic-scratch3-add-variable]]]

--- /task ---

--- task ---

Kannst du die Punktzahl des Spielers verfolgen? Die Spieler sollten Punkte bekommen, wenn sie auf Geister klicken und sie fangen.

Jedes Mal, wenn ein Spieler auf ein Gespenst klickt, sollte sein Punktestand erhöht werden.

![Punktestand erhöhen](images/ghost-score-test.png)

--- hints ---
 --- hint ---

`Wenn die grüne Flagge angeklickt wird`{:class="block3events"}, sollte deine `Punkte`{:class="block3variables"} Variable `auf 0 gesetzt`{:class="block3variables"} werden. Am Besten fügst Du diesen Code der Bühne hinzu.

`Wenn die Geist-Figur angeklickt wird`{:class="block3events"}, sollte sich der Wert der Variable `Punkte`{:class="block3variables"} um `1 ändern`{:class="block3variables"}.

--- /hint --- --- hint --- Hier sind die Codeblöcke die du brauchst: ![Hintergrund-Symbol](images/ghost-backdrop.png)

```blocks3
set [Punkte v] to (0)

when flag clicked
```

![Geist-Figur](images/ghost-sprite.png)

```blocks3
change [Punkte v] by (1)
```

--- /hint --- --- hint --- ![Hintergrund-Symbol](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [Punkte v] to (0)
```

![Geist-Figur](images/ghost-sprite.png)

```blocks3
When this sprite clicked
hide
+ change [Punkte v] by (1)
```

--- /hint --- --- /hints ---

--- /task ---