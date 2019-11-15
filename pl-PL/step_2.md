## Animuj ducha

--- task ---

Otwórz nowy projekt w Scratch-u.

[[[generic-scratch3-new-project]]]

--- /task ---

--- task ---

Dodaj nowego duszka przedstawiającego ducha i odpowiednie tło sceniczne.

![zrzut ekranu](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

--- /task ---

--- task ---

Dodaj kod do duszka ducha, aby pojawiał się i znikał na zawsze po kliknięciu zielonej flagi.

--- hints ---
 --- hint ---

Po `zielona flaga kliknięciu`{:class="block3events"}, twój duch powinien `ukryj`{:class="block3looks"} przez `jeden sekund`{:class="block3control"}, a następnie `pokaż`{:class="block3looks"} przez `jedną sekundę`{:class="block3control"}. Musi to zrobić `zawsze`{:class="block3control"}. --- /hint --- --- hint ---

Oto potrzebne bloki kodu: ![duszek ducha](images/ghost-sprite.png)

```blocks3
ukryj

pokaż

zawsze
koniec

czekaj (1) sekund

czekaj (1) sekund

kiedy kliknięto zieloną flagę
```

--- /hint --- --- hint --- Twój kod powinien wyglądać tak: ![duszek ducha](images/ghost-sprite.png)

```blocks3
kiedy kliknięto zieloną flagę
zawsze
ukryj
czekaj (1) sekund
pokaż
czekaj (1) sekund
koniec
```

--- /hint --- --- /hints ---

--- /task ---

--- task ---

Przetestuj i zapisz swój projekt.

[[[generic-scratch3-saving]]]

--- /task ---