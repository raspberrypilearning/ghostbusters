## Een spook laten bewegen

--- task ---

Open een nieuw leeg Scratch-project.

[[[generic-scratch3-new-project]]]

--- /task ---

--- task ---

Voeg een nieuwe Spook Sprite (Ghost) toe, en een geschikte achtergrond.

![schermafdruk](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

--- /task ---

--- task ---

Voeg code toe aan je spook sprite zodat het spook steeds verschijnt en verdwijnt als op de groene vlag wordt geklikt.

--- hints ---
 --- hint ---

`Wanneer op de groene vlag wordt geklikt`{:class="block3events"}, `verdwijn`t je spook {:class="block3looks"} gedurende `één seconde`{:class="block3control"} en vervolgens `verschijn`{:class="block3looks"}t je spook gedurende `één seconde`{:class="block3control"}. Het moet in een `herhaal`{:class="block3control"} blok.
--- /hint ---
 --- hint ---

Dit zijn de codeblokken die je nodig hebt: ![spook-sprite](images/ghost-sprite.png)

```blocks3
hide

show

forever
end

wait (1) seconds

wait (1) seconds

when flag clicked
```

--- /hint --- --- hint --- Zo zou je nieuwe code er uit moeten zien: ![spook-sprite](images/ghost-sprite.png)

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

Test en sla je project op.

[[[generic-scratch3-saving]]]

--- /task ---