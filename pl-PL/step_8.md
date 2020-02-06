## Dodaj licznik czasu

Teraz dodamy zegar, aby gracz miał tylko dziesięć sekund na złapanie jak największej liczby duchów.

\--- task \---

Utwórz nową zmienną o nazwie "czas".

\--- /task \---

\--- task \---

Czy możesz dodać licznik czasu do sceny, aby dać graczowi tylko 10 sekund na złapanie duchów?

Twój licznik czasu powinien:

+ Zacznij od 10 sekund
+ Odliczaj co sekundę

Gra powinna się zatrzymać, gdy czas dojdzie do 0.

\--- hints \--- \--- hint \---

`When the green flag is clicked`{:class="block3events"}, your `time`{:class="block3variables"} variable should be `set to 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}.

-- /hint \--- \--- hint \---

Here are the code blocks you need to use:

![ghost-sprite](images/ghost-backdrop.png)

```blocks3
stop [all]

< [] = [] >

ustaw [czas v] na [10]

zmień [czas v] o(-1)

(czas)

czekaj (1) sekund

powtórzyć do < >
koniec

po kliknięciu flagi

```

-- /hint \--- \--- hint \---

Here is the code you should add to create a timer:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
kiedy flaga kliknięta
ustaw [czas v] na [10]
powtarzaj, aż < (czas) = [0] >
czekaj (1) sekund
zmiań [czas v] o (-1)
koniec
zatrzymaj [all]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

If your game is too easy, you can:

+ Dać graczowi mniej czasu
+ Sprawić, aby duchy pojawiały się rzadziej
+ Zmniejszyć duchy

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---