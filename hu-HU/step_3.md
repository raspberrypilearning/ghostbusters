## Véletlenül feltűnő szellemek

Jelenleg a szellemed nagyon könnyű elkapni, mert nem mozog!

--- task ---

Tudnál hozzáadni olyan kódot, hogy a szellemed véletlenszerű pozíciókban jelenjen meg a játéktérben?

--- hints ---


--- hint ---

Minden alkalommal, amikor a szellemed megjelenik véletlenszerű pozícióba kell `mennie`{:class="block3motion"} a játéktéren.

--- /hint --- --- hint ---

A kódblokkok két csoportját tudnád használni ebben az esetben. Válassz kedved szerint.

![szellem-szereplő](images/ghost-sprite.png)

Add hozzá ezt a blokkkészletet a szellem szerelőhöz:

```blocks3
ugorj (véletlen v) helyre
```

Vagy add hozzá ezt a szereplőhöz:

```blocks3
ugorj ide: x: (14) y: (50)

(véletlen (1) és (10) között)

(véletlen (1) és (10) között)
```

--- /hint ---

--- hint ---

A kódod így nézhet ki:

![szellem-szereplő](images/ghost-sprite.png)

```blocks3
⚑ -ra kattintáskor
mindig 
tűnj el
várj (1) mp-et
ugorj (véletlen helyre v) helyére
jelenj meg
várj (1) mp-et
end
```

Vagy így nézhet ki:

![szellem-szereplő](images/ghost-sprite.png)

```blocks3
⚑ -ra kattintáskor
mindig 
tűnj el
várj (1) mp-et
ugorj ide: x: (véletlen (-150) és (150) között) y: (véletlen (-150) és (150) között)
jelenj meg
várj (1) mp-et
end
```

--- /hint --- --- /hints ---

--- /task ---