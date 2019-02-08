## Add a timer

Now you're going to add a timer so that the player only has ten seconds to catch as many ghosts as possible.

\--- task \---

Maak een nieuwe variabele met de naam 'time'.

\--- /task \---

\--- task \----

Can you add a timer to your Stage to give your player only 10 seconds to catch ghosts?

Je timer zou moeten:

+ Beginnen met 10 seconden
+ Elke seconde aftellen

Het spel zou moeten stoppen als de timer op 0 komt.

\--- hints \--- \--- hint \--- `When the green flag is clicked`{:class="block3events"}, your `time`{:class="block3variables"} variable should be `set to 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}. \--- /hint \--- \--- hint \--- Here are the code blocks you need to use: ![ghost-sprite](images/ghost-backdrop.png)

```blocks3
stop [all]

< [ ] = [ ] >

set [time v] to [10]

change [time v] by (-1)

(time)

wait (1) seconds

repeat until < >
end

when flag clicked

```

\--- /hint \--- \--- hint \--- Here is the code you should add to create a timer: ![backdrop icon](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [time v] to [10]
repeat until < (time) = [0] >
wait (1) seconds
change [time v] by (-1)
end
stop [all]
```

\--- /hint \--- \--- /hints \---

-- /task \---

\--- task \----

Ask a friend to test your game. How many points can they score?

\--- /task \---

Als je spel te gemakkelijk is, kun je:

+ De speler minder tijd geven
+ De spoken minder vaak laten verschijnen
+ De spoken kleiner maken

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---