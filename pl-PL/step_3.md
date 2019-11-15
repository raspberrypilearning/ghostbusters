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
Idź do (losowa pozycja v)
```

Lub dodaj ten do swojego duszka:

```blocks3
Idź do x: (14) y: (50)

(losuj liczbę od (1) do (10))

(losuj liczbę od (1) do (10))
```

--- /hint ---

--- hint ---

Twój kod może wyglądać tak:

![duszek ducha](images/ghost-sprite.png)

```blocks3
kiedy kliknięto zieloną flagę
zawsze 
ukryj
czekaj (1) sekund
Idź do (losowa pozycja v)
pokaż
czekaj (1) sekund
koniec
```

Lub może wyglądać tak:

![duszek ducha](images/ghost-sprite.png)

```blocks3
kiedy kliknięto zieloną flagę
zawsze 
ukryj
czekaj (1) sekund
Idź do x: (losuj liczbę od (-150) do (150)) y: (losuj liczbę od (-150) do (150))
pokaż
czekaj (1) sekund
koniec
```

--- /hint --- --- /hints ---

--- /task ---