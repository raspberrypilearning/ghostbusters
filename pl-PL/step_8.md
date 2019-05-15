## Dodaj licznik czasu

Now you're going to add a timer so that the player only has ten seconds to catch as many ghosts as possible.

\--- task \---

Utwórz nową zmienną o nazwie "czas".

\--- /task \---

\--- task \---

Czy możesz dodać licznik czasu do sceny, aby dać graczowi tylko 10 sekund na złapanie duchów?

Twój licznik czasu powinien:

+ Zacznij od 10 sekund
+ Odliczaj co sekundę

Gra powinna się zatrzymać, gdy czas dojdzie do 0.

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

\--- /task \---

\--- task \---

Poproś znajomego, aby przetestował twoją grę. Ile punktów można zdobyć?

\--- /task \---

Jeśli Twoja gra jest zbyt łatwa, możesz:

+ Dać graczowi mniej czasu
+ Sprawić, aby duchy pojawiały się rzadziej
+ Zmniejszyć duchy

\--- task \---

Zmień i przetestuj swoją grę kilka razy, aż będziesz zadowolony z poziomu trudności.

\--- /task \---