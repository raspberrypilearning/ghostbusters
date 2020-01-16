## Ein Gespenst lebendig werden lassen

\--- task \---

Öffne ein neues Scratch-Projekt.

[[[generic-scratch3-new-project]]]

\--- /task \---

\--- task \---

Wähle eine neue Gespenster-Figur und einen passenden Bühnenhintergrund aus.

![Screenshot](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

\--- /task \---

\--- task \---

Füge deiner Gespenster-Figur solche Code hinzu, dass der Geist immerwieder auftaucht und verschwindet, wenn die grüne Flagge angeklickt wird.

\--- hints \--- \--- hint \---

Sobald die `grüne Flagge angeklickt wird`{:class="block3events"}, sollte sich dein Geist für `eine Sekunde`{:class="block3control"} `verstecken`{:class="block3looks"} und sich dann für `eine Sekunde`{:class="block3control"} `zeigen`{:class="block3looks"}. Das muss er `fortlaufend`{:class=”block3control”} wiederholen.

\--- /hint \--- \--- hint \---

Here are the code blocks you need:

![Geist-Figur](images/ghost-sprite.png)

```blocks3
verstecke dich

zeige dich

wiederhole fortlaufend
ende

warte (1) Sekunden

warte (1) Sekunden

Wenn die Flagge angeklickt wird
```

\--- /hint \--- \--- hint \---

This is what your code should look like:

![Geist-Figur](images/ghost-sprite.png)

```blocks3
Wenn die Flagge angeklickt wird
wiederhole fortlaufend
verstecke dich
warte (1) Sekunden
zeige dich
warte (1) Sekunden
ende
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Test and save your project.

[[[generic-scratch3-saving]]]

\--- /task \---