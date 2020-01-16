## Een tijdklok toevoegen

Nu ga je een tijdklok toevoegen zodat de speler maar tien seconden heeft om zoveel mogelijk spoken te vangen.

\--- task \---

Maak een nieuwe variabele met de naam 'tijd'.

\--- /task \---

\--- task \----

Kun je een tijdklok toevoegen aan het speelveld zodat de speler maar 10 seconden de tijd heeft om zoveel mogelijk spoken te vangen?

Je timer zou moeten:

+ Beginnen met 10 seconden
+ Elke seconde aftellen

Het spel zou moeten stoppen als de timer op 0 komt.

\--- hints \--- \--- hint \---

`When the green flag is clicked`{:class="block3events"}, your `time`{:class="block3variables"} variable should be `set to 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need to use:

![spook-sprite](images/ghost-backdrop.png)

```blocks3
stop [alle]

< [ ] = [ ] >

maak [tijd v] [10]

verander [tijd v] met (-1)

(tijd)

wacht (1) sec.

herhaal tot < >
end

wanneer groene vlag wordt aangeklikt

```

\--- /hint \--- \--- hint \---

Here is the code you should add to create a timer:

![achtergrond pictogram](images/ghost-backdrop.png)

```blocks3
wanneer groene vlag wordt aangeklikt
maak [tijd v] [10]
herhaal tot < (tijd) = [0] >
wacht (1) sec.
verander [tijd v] met (-1)
end
stop [alle]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \----

Ask a friend to test your game. How many points can they score?

\--- /task \---

If your game is too easy, you can:

+ De speler minder tijd geven
+ De spoken minder vaak laten verschijnen
+ De spoken kleiner maken

\--- task \----

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---