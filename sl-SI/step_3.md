## Naključni duhovi

Tvoj duhec je trenutno še zelo lahko ujeti, ker se ne premika!

--- task ---

Ali lahko svojemu duhu dodaš kodo, tako da ne ostane vedno na istem položaju, temveč se pojavi na naključnih položajih na odru?

--- hints ---

--- hint ---

Vsakič, preden se tvoja figura duhca povavi, bi ji moral ukazati `pojdi na`{:class="block3motion"} naključni položaj na odru.

--- /hint --- --- hint ---

Obstajata dva niza blokov kode, ki jih lahko za to uporabiš. Izberi tistega, ki ti bolj ustreza.

![figura-duhca](images/ghost-sprite.png)

Figuri duhca dodaj ta blok:

```blocks3
pojdi na (naključno mesto v)
```

Ali pa duhu dodaj te bloke:

```blocks3
pojdi na x: (14) y: (50)

naključno število med (1) in (10)

naključno število med (1) in (10)
```

--- /hint ---

--- hint ---

Tvoja koda bi lahko izgledala tako:

![figura-duhca](images/ghost-sprite.png)

```blocks3
ko kliknemo na zastavico
ponavljaj
skrij
počakaj (1) sekunde
pojdi na (naključna mesto v)
pokaži
počakaj (1) sekunde
konec
```

Lahko pa bi bila videti tudi tako:

![figura-duhca](images/ghost-sprite.png)

```blocks3
ko kliknemo na zastavico
ponavljaj
skrij
počakaj (1) sekunde
pojdi na x: (naključno število med (-150) in (150)) y: (naključno število med (-150) in (150))
pokaži
počakaj (1) sekunde
konec
```

--- /hint --- --- /hints ---

--- /task ---