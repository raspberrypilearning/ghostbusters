## Beweeg een spook

--- task ---

Open een nieuw leeg Scratch-project.

[[[generic-scratch3-new-project]]]

--- /task ---

--- task ---

Voeg een nieuwe Spook Sprite (Ghost) toe, en een geschikte achtergrond.

![screenshot](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

--- /task ---

--- task ---

Voeg code toe aan je spook sprite zodat het spook steeds verschijnt en verdwijnt als op de groene vlag wordt geklikt.

--- hints ---
--- hint ---

`Wanneer op de groene vlag wordt geklikt`{:class="block3events"}, `verdwijn`{:class="block3looks"} je spook gedurende `één seconde`{:class="block3control"} en vervolgens `verschijn`{:class="block3looks"} je spook gedurende `één seconde`{:class="block3control"}. Het moet in een `herhaal`{:class="block3control"} blok.
--- /hint ---
--- hint ---

Dit zijn de codeblokken die je nodig hebt: ![spook-sprite](images/ghost-sprite.png)

```blocks3
verdwijn

verschijn

herhaal
end

wacht (1) sec.

wacht (1) sec.

wanneer groene vlag wordt aangeklikt
```

--- /hint --- 
--- hint --- 

Hier is hoe je code eruit zou moeten zien: ![spook-sprite](images/ghost-sprite.png)

```blocks3
wanneer groene vlag wordt aangeklikt
herhaal
verdwijn
wacht (1) sec.
verschijn
wacht (1) sec.
end
```

--- /hint ---
--- /hints ---

--- /task ---

--- task ---

Test en sla je project op.

[[[generic-scratch3-saving]]]

--- /task ---