## Dodaj licznik czasu

Teraz dodamy zegar, aby gracz miał tylko dziesięć sekund na złapanie jak największej liczby duchów.

--- task ---

Utwórz nową zmienną o nazwie "czas".

--- /task ---

--- task ---

Czy możesz dodać licznik czasu do sceny, aby dać graczowi tylko 10 sekund na złapanie duchów?

Twój licznik czasu powinien:

+ Zacznij od 10 sekund
+ Odliczaj co sekundę

Gra powinna się zatrzymać, gdy czas dojdzie do 0.

--- hints ---
 --- hint --- `Kiedy kliknięta jest zielona flaga`{:class="block3events"}, twoja zmienna `czas`{:class="block3variables"} powinna być ustawiona na `na 10`{:class="block3variables"}. Powinna następnie `zmień o -1`{:class="block3variables"} co sekundę `, aż dojdzie do 0`{:class="block3control"}.
--- /hint ---
 --- hint --- Oto potrzebne bloki kodu: ![duszek ducha](images/ghost-backdrop.png)

```blocks3
stop [wszystko]

< [ ] = [ ] >

set [czas v] to [10]

change [czas v] by (-1)

(czas)

wait (1) seconds

repeat until < >
end

when flag clicked

```

--- /hint --- --- hint --- Oto kod, który należy dodać, aby utworzyć zegar: ![ikona tła](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [czas v] to [10]
repeat until < (czas) = [0] >
wait (1) seconds
change [czas v] by (-1)
end
stop [wszystko]
```

--- /hint --- --- /hints ---

--- /task ---

--- task ---

Poproś znajomego, aby przetestował twoją grę. Ile punktów można zdobyć?

--- /task ---

Jeśli Twoja gra jest zbyt łatwa, możesz:

+ Dać graczowi mniej czasu
+ Sprawić, aby duchy pojawiały się rzadziej
+ Zmniejszyć duchy

--- task ---

Zmień i przetestuj swoją grę kilka razy, aż będziesz zadowolony z poziomu trudności.

--- /task ---