## Animiere ein Gespenst

--- task ---

Öffne ein neues Scratch-Projekt.

[[[generic-scratch3-new-project]]]

--- /task ---

--- task ---

Wähle eine neue Gespenster-Figur und einen passenden Bühnenhintergrund aus.

![Screenshot](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

--- /task ---

--- task ---

Füge deiner Gespenster-Figur solche Code hinzu, dass der Geist immerwieder auftaucht und verschwindet, wenn die grüne Flagge angeklickt wird.

--- hints ---
 --- hint ---

Sobald die `grüne Flagge angeklickt wird`{:class="block3events"}, sollte sich dein Geist für `eine Sekunde`{:class="block3control"} `verstecken`{:class="block3looks"} und sich dann für `eine Sekunde`{:class="block3control"} `zeigen`{:class="block3looks"}. Das muss er `fortlaufend`{:class=”block3control”} wiederholen.
--- /hint ---
 --- hint ---

Hier sind die Codeblöcke die du brauchst: ![Geist-Figur](images/ghost-sprite.png)

```blocks3
hide

show

forever
end

wait (1) seconds

wait (1) seconds

when flag clicked
```

--- /hint --- --- hint --- So sollte dein Code aussehen: ![Geist-Figur](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
show
wait (1) seconds
end
```

--- /hint --- --- /hints ---

--- /task ---

--- task ---

Teste und speichere nun dein Projekt.

[[[generic-scratch3-saving]]]

--- /task ---