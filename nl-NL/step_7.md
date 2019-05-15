## Een score toevoegen

Nu ga je je spel interessanter maken door de score bij te houden!

--- task ----

Maak een nieuwe variabele met de naam `score`{:class="block3variables"}.

[[[generic-scratch3-add-variable]]]

--- /task ---

--- task ----

Kun je de score van de spelers bijhouden? Spelers zouden punten moeten scoren als ze spoken vangen door er op te klikken.

Elke keer dat een speler op een spook klikt, zou de score moeten stijgen.

![Score ophogen](images/ghost-score-test.png)

--- hints ---
--- hint ---

`Wanneer op de groene vlag wordt geklikt`{:class="block3events"}, moet de `score`{:class="block3variables"} variabele op `0`{:class="block3variables"} gezet worden. Het speelveld is de beste plaats om deze code neer te zetten.

`Wanneer op de Spook Sprite wordt geklikt`{:class="block3events"}, moet de `score `{:class="block3variables"} `met 1 worden opgehoogd`{:class="block3data"}.

--- /hint --- 
--- hint --- 

Dit zijn de codeblokken die je nodig hebt: ![achtergrond pictogram](images/ghost-backdrop.png)

```blocks3
maak [score v] (0)

wanneer groene vlag wordt aangeklikt
```

![spook-sprite](images/ghost-sprite.png)

```blocks3
verander [score v] met (1)
```

--- /hint --- 
--- hint --- 

![achtergrond pictogram](images/ghost-backdrop.png)

```blocks3
wanneer groene vlag wordt aangeklikt
maak [score v] (0)
```

![spook-sprite](images/ghost-sprite.png)

```blocks3
Wanneer op deze sprite wordt geklikt
verdwijn

+ verander [score v] met (1)
```

--- /hint ---
--- /hints ---

--- /task ---