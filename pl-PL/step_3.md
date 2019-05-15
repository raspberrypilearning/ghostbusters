## Losowe duchy

Twój duch jest naprawdę łatwy do złapania, ponieważ się nie porusza!

\--- task \---

Can you add code to your ghost so that, instead of staying in the same position, the ghost appears at random positions on the Stage?

\--- hints \---

\--- hint \---

Each time before your ghost appears, it should `go to`{:class="block3motion"} a random position on the Stage.

-- /hint \--- \--- hint \---

Istnieją dwa zestawy bloków kodu, których możesz użyć tutaj. Wybierz zestaw, który preferujesz.

![ghost-sprite](images/ghost-sprite.png)

Either add this set of blocks to your ghost sprite:

```blocks3
idź do (losowa pozycja v)
```

Lub dodaj ten do swojego duszka:

```blocks3
przejdź do x: (14) y: (50)

wybierz losowo (1) do (10)

wybierz losowo (1) do (10)
```

\--- /hint \---

\--- hint \---

Twój kod może wyglądać tak:

![ghost-sprite](images/ghost-sprite.png)

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

![ghost-sprite](images/ghost-sprite.png)

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

\--- /hint \--- \--- /hints \---

\--- /task \---