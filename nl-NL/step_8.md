## Een tijdklok toevoegen

Nu ga je een tijdklok toevoegen zodat de speler maar tien seconden heeft om zoveel mogelijk spoken te vangen.

--- task ---

Maak een nieuwe variabele met de naam 'tijd'.

--- /task ---

--- task ---

Kun je een tijdklok toevoegen aan het speelveld zodat de speler maar 10 seconden de tijd heeft om zoveel mogelijk spoken te vangen?

Je timer zou moeten:

+ Beginnen met 10 seconden
+ Elke seconde aftellen

Het spel zou moeten stoppen als de timer op 0 komt.

--- hints ---
 --- hint --- `Wanneer op de groene vlag wordt geklikt`{:class="block3events"}, zou de `tijd`{:class="block3variables"} variabele op `10`{:class="block3variables"} moeten worden gezet. Het zou dan elke seconde moeten `veranderen met -1`{:class="block3variables"} totdat deze `0 bereikt`{:class="block3control"}.
--- /hint ---
 --- hint --- Dit zijn de codeblokken die je nodig hebt: ![spook-sprite](images/ghost-backdrop.png)

```blocks3
stop [alle]

< [ ] = [ ] >

set [tijd v] to [10]

change [tijd v] by (-1)

(tijd)

wait (1) seconds

repeat until < >
end

when flag clicked

```

--- /hint --- --- hint --- Hier is de code die je moet toevoegen om een tijdklok te maken: ![achtergrond pictogram](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [tijd v] to [10]
repeat until < (rijd) = [0] >
wait (1) seconds
change [tijd v] by (-1)
end
stop [alle]
```

--- /hint --- --- /hints ---

--- /task ---

--- task ---

Vraag een vriend om je spel te testen. Hoeveel punten kunnen ze scoren?

--- /task ---

Als je spel te gemakkelijk is, kun je:

+ De speler minder tijd geven
+ De spoken minder vaak laten verschijnen
+ De spoken kleiner maken

--- task ---

Verander en test je spel een paar keer totdat je tevreden bent met de moeilijkheidsgraad.

--- /task ---