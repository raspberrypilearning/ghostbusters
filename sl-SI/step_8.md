## Dodaj časovnik

Sedaj boš dodal-a štoparico, tako da bo igralec imel samo deset sekund, v katerih mora ujeti čim več duhov.

--- task ---

Ustvari novo spremenljivko, imenovano »čas«.

--- /task ---

--- task ---

Ali lahko dodaš tvojemu odru časovnik, ki bo igralcu omogočil le 10 sekund, za lovljenje duhov?

Tvoj časovnik mora:

+ Začeti pri 10 sekund
+ Odštevati po eno skundo

Igra se mora ustaviti, ko časovnik doseže 0.

--- hints --- 
--- hint ---

`Ko kliknemo na zastavico`{:class="block3events"}, spremenljivko `čas`{:class="block3variables"} `nastavi na 10`{:class="block3variables"}. Nato `spremeni čas za -1`{:class="block3variables"}, dokler `ne doseže 0`{:class="block3control"}.

--- /hint --- 
--- hint ---

To so bloki kode, ki jih potrebuješ:

![figura-duhca](images/ghost-backdrop.png)

```blocks3
ustavi [vse]

<[ ] = [ ]>

nastavi [čas v] na [10]

spremeni [čas v] za (-1)

(čas)

počakaj (1) sekund

ponavljaj do <>
end

ko je kliknjena zelena zastavica

```

--- /hint --- 
--- hint ---

Takšna je koda za dodajanje časovnika:

![ikona ozadja](images/ghost-backdrop.png)

```blocks3
ko je kliknjena zelena zastavica
nastavi [čas V] na [10]
ponavljaj do < (čas) = [0] >
počakaj (1) sekund
spremeni [čas V] za (-1)
konec
ustavi [vse]
```

--- /hint --- 
--- /hints ---

--- /task ---

--- task ---

Prosi prijatelja, da preizkusi tvojo igro. Koliko točk lahko doseže?

--- /task ---

Če je tvoja igra preveč enostavna, lahko:

+ Daš igralcu manj časa
+ Narediš, da se duhovi pojavljajo manj pogosto
+ Zmanjšaš figure duhcev

--- task ---

Spreminjaj in preizkušaj svojo igro, dokler nisi zadovoljen z njeno težavnosto stopnjo.

--- /task ---