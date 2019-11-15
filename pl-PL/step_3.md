## Losowe duchy

Twój duch jest naprawdę łatwy do złapania, ponieważ się nie porusza!

--- task ---

Czy możesz dodać kod do swojego ducha, aby zamiast pozostawać w tej samej pozycji, duch pojawiał się w losowych miejscach na scenie?

--- hints ---


--- hint ---

Za każdym razem, zanim pojawi się twój duch, powinien `przejść`{:class="block3motion"} do losowej pozycji na scenie.

--- /hint --- --- hint ---

Istnieją dwa zestawy bloków kodu, których możesz użyć tutaj. Wybierz zestaw, który preferujesz.

![duszek ducha](images/ghost-sprite.png)

Dodaj ten zestaw bloków do twojego duszka:

```blocks3
idź do (losowa pozycja v)
```

Lub dodaj ten do swojego duszka:

```blocks3
przejdź do x: (14) y: (50)

wybierz losowo (1) do (10)

wybierz losowo (1) do (10)
```

--- /hint ---

--- hint ---

Twój kod może wyglądać tak:

![duszek ducha](images/ghost-sprite.png)

```blocks3
kiedy flaga kliknięta
zawsze
ukryj
czekaj (1) sekundy
idź do (losowa pozycja v)
pokaż
czekaj (1) sekundy
koniec
```

Lub może wyglądać tak:

![duszek ducha](images/ghost-sprite.png)

```blocks3
kiedy flaga kliknięta
zawsze
ukryj
czekaj (1) sekundy
przejdź do x: (wybierz losowo (-150) do (150)) y: (wybierz losowo (-150) do (150))
pokaż
czekaj (1) sekund
koniec
```

--- /hint --- --- /hints ---

--- /task ---