## Fantômes aléatoires

Ton fantôme est vraiment facile à attraper en ce moment, parce qu'il ne bouge pas!

--- task ---

Peux-tu ajouter du code à ton fantôme pour que, au lieu de rester dans la même position, le fantôme apparaisse à des positions aléatoires sur la scène?

--- hints ---


--- hint ---

Chaque fois avant que ton fantôme apparaît, il faut `aller à`{:class="block3motion"} une position aléatoire sur la scène.

--- /hint --- --- hint ---

Il y a deux ensembles de blocs de code que tu peux utiliser ici. Choisis le jeu que tu préfères.

![sprite-fantôme](images/ghost-sprite.png)

Soit ajoute cet ensemble de blocs à ton sprite fantôme:

```blocks3
go to (position aléatoire v)
```

Ou ajoute celui-ci à ton sprite:

```blocks3
go to x: (14) y: (50)

pick random (1) to (10)

pick random (1) to (10)
```

--- /hint---

--- hint ---

Ton code pourrait ressembler à ceci:

![sprite-fantôme](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to (position aléatoire v)
show
wait (1) seconds
end
```

Ou pourrait ressembler à ceci:

![sprite-fantôme](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to x: (pick random (-150) to (150)) y: (pick random (-150) to (150))
show
wait (1) seconds
end
```

--- /hint --- --- /hints ---

--- /task ---