## Zufällige Gespenster

Dein Geist ist im Moment wirklich leicht zu fangen, weil er sich nicht bewegt!

--- task ---

Kannst du deinem Geist Code hinzufügen, dass er nicht an der selben Stelle auf der Bühne bleibt, sondern an zufälligen Positionen auf der Bühne erscheint?

--- hints ---


--- hint ---

Jedes Mal, bevor dein Geist erscheint, sollte er zu einer zufälligen Position auf der Bühne `gehen`{:class="block3motion"}.

--- /hint --- --- hint ---

Es gibt zwei Kombinationen von Codeblöcken, die du hier verwenden kannst. Suche dir die Kombination aus, die dir am besten gefällt.

![Geist-Figur](images/ghost-sprite.png)

Füge deiner Geister-Figur entweder diesen Block hinzu:

```blocks3
go to (Zufallsposition v)
```

Oder füge diese Blöcke zu deiner Figur:

```blocks3
go to x: (14) y: (50)

pick random (1) to (10)

pick random (1) to (10)
```

--- /hint ---

--- hint ---

Dein Code sollte entweder so aussehen:

![Geist-Figur](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to (Zufallsposition v)
show
wait (1) seconds
end
```

Oder er könnte so aussehen:

![Geist-Figur](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to x: (pick random (-150) to (150)) y: (pick random (-150) to (150))
show
wait (1) seconds
end
```

--- /hint --- --- /hints ---

--- /task ---