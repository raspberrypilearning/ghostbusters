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
hide

show

forever
end

wait (1) seconds

wait (1) seconds

when flag clicked
```

--- /hint --- --- hint --- Twój kod powinien wyglądać tak: ![duszek ducha](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
show
wait (1) seconds
end
```

--- /hint --- --- /hints ---

--- /task ---

--- task ---

Przetestuj i zapisz swój projekt.

[[[generic-scratch3-saving]]]

--- /task ---