## Animálj egy szellemet

--- task ---

Nyiss meg egy új üres Scratch projektet.

[[[generic-scratch3-new-project]]]

--- /task ---

--- task ---

Adj hozzá egy új szellem szereplőt és egy megfelelő háttérképet.

![képernyőkép](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

--- /task ---

--- task ---

Adj hozzá olyan kódot a szellem szereplőhöz, hogy a szellem folyamatosan megjelenjen és eltűnjön, miután a zöld zászlóra kattintunk.

--- hints ---
 --- hint ---

A `zöld zászlóra kattintás`{:class="block3events"} után, a szellemednek `el kell tűnnie`{:class="block3looks"} `egy másodpercre`{:class="block3control"}, majd `megjelennie`{:class="block3looks"} `egy másodpercre`{:class="block3control"}. Ezt `mindig`{:class="block3control"} kell tennie.
--- /hint ---
 --- hint ---

Íme a szükséges kódblokkok: ![szellem-szereplő](images/ghost-sprite.png)

```blocks3
tűnj el

jelenj meg

mindig
end

várj (1) mp-et

várj (1) mp-et

⚑ -ra kattintáskor
```

--- /hint --- --- hint --- Így kell kinéznie a kódodnak: ![szellem-szereplő](images/ghost-sprite.png)

```blocks3
⚑ -ra kattintáskor
mindig
tűnj el
várj (1) mp-et
jelenj meg
várj (1) mp-et
end
```

--- /hint --- --- /hints ---

--- /task ---

--- task ---

Teszteld és mentsd el a projekted.

[[[generic-scratch3-saving]]]

--- /task ---