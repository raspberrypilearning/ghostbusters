## Animuj ducha

\--- task \---

Otwórz nowy projekt w Scratch-u.

[[[generic-scratch3-new-project]]]

\--- /task \---

\--- task \---

Dodaj nowego duszka przedstawiającego ducha i odpowiednie tło sceniczne.

![zrzut ekranu](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

\--- /task \---

\--- task \---

Dodaj kod do duszka ducha, aby pojawiał się i znikał na zawsze po kliknięciu zielonej flagi.

\--- hints \--- \--- hint \---

Once the `green flag is clicked`{:class="block3events"}, your ghost should `hide`{:class="block3looks"} for `one second`{:class="block3control"} and then `show`{:class="block3looks"} for `one second`{:class="block3control"}. Musi to zrobić `zawsze`{: class = "block3control"}.

-- /hint \--- \--- hint \---

Here are the code blocks you need:

![duszek ducha](images/ghost-sprite.png)

```blocks3
ukryj

pokaż

zawsze
koniec

czekaj (1) sekund

czekaj (1) sekund

gdy kliknięta flaga
```

-- /hint \--- \--- hint \---

This is what your code should look like:

![duszek ducha](images/ghost-sprite.png)

```blocks3
kiedy flaga kliknięta
zawsze
ukryj
czekaj (1) sekundy
pokaż
czekaj (1) sekundy
koniec
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Test and save your project.

[[[generic-scratch3-saving]]]

\--- /task \---