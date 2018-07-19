## Eine Punktzahl hinzufügen

Lass uns die Dinge interessanter machen, indem wir Punkte zählen!

\--- task \---

Erstelle eine neue Variable namens "Punkte".

[[[generic-scratch-add-variable]]]

\--- /task \---

\--- task \---

Kannst du den Punktestand des Spielers mitschreiben? Die Spieler sollten Punkte bekommen, wenn sie auf Geister klicken, um sie zu fangen.

Jedes Mal, wenn ein Spieler auf einen Geist klickt, sollte sein Punktestand erhöht werden.

![Increasing score](images/ghost-score-test.png)

\--- hints \--- \--- hint \--- `When the green flag is clicked`{:class=”blockevents”}, your `score`{:class=”blockdata”} variable should be `set to 0`{:class=”blockdata”}. The Stage is the best place to add this code. `When the ghost sprite is clicked`{:class=”blockevents”}, the `score`{:class=”blockdata”} should be `changed by 1`{:class=”blockdata”}. \--- /hint \--- \--- hint \--- Here are the code blocks you will need to use: ![screenshot](images/ghost-score-blocks.png) \--- /hint \--- \--- hint \--- Here's how to score points by clicking ghosts: ![screenshot](images/ghost-score-code.png) \--- /hint \--- \--- /hints \---

\--- /task \---