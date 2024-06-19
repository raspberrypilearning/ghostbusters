## Dodaj wynik

Teraz sprawisz, że twoja gra będzie bardziej interesująca dzięki zbieraniu punktów!

--- task ---

Utwórz nową zmienną o nazwie `wynik`{:class="block3variables"}.

[[[generic-scratch3-add-variable]]]

--- /task ---

--- task ---

Czy możesz śledzić wynik gracza? Gracze powinni zdobywać punkty, łapiąc duchy poprzez kliknięcie na nie.

Za każdym razem, gdy gracz kliknie na ducha, jego wynik powinien wzrosnąć.

![Zwiększenie wyniku](images/ghost-score-test.png)

--- hints ---
 --- hint ---

`Po kliknięciu zielonej flagi`{:class="block3events"} twoja zmienna `wynik`{:class="block3variables"} powinna być `ustawiona na 0`{:class="block3variables"}. Scena jest najlepszym miejscem do dodania tego kodu.

`Po kliknięciu duszka ducha`{:class="block3events"}, zmienna `wynik`{:class="block3variables"} powinna być `zmieniona o 1`{:class="block3variables"}.

--- /hint --- --- hint --- Oto potrzebne bloki kodu: ![ikona tła](images/ghost-backdrop.png)

```blocks3
set [wynikl v] to (0)

when flag clicked
```

![duszek ducha](images/ghost-sprite.png)

```blocks3
change [wynik v] by (1)
```

--- /hint --- --- hint ---![ikona tła](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [wynik v] to (0)
```

![duszek ducha](images/ghost-sprite.png)

```blocks3
When this sprite clicked
hide
+ change [wynik v] by (1)
```

--- /hint --- --- /hints ---

--- /task ---