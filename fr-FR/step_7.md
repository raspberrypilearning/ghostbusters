## Ajouter un score

Maintenant, tu vas rendre ton jeu plus intéressant en gardant le score!

--- task ---

Crée une nouvelle variable appelée `score`{:class="block3variables"}.

[[[generic-scratch3-add-variable]]]

--- /task ---

--- task ---

Peux-tu suivre le score du joueur? Les joueurs doivent marquer des points lorsqu'ils cliquent sur des fantômes pour les attraper.

Chaque fois qu'un joueur clique sur un fantôme, son score doit augmenter.

![Augmenter le score](images/ghost-score-test.png)

--- hints ---
 --- hint ---

`Lorsque le drapeau vert est cliqué`{:class="block3events"}, ta variable `score`{:class="block3variables"} doit être `définit sur 0`{:class="block3variables"}. La scène est le meilleur endroit pour ajouter ce code.

`Lorsque le sprite fantôme est cliqué`{:class="block3events"}, la variable `score`{:class="block3variables"} devrait être `incrémentée de 1`{:class="block3variables"}.

--- /hint --- --- hint --- Voici les blocs de code dont tu as besoin : ![icône de l'arrière-plan](images/ghost-backdrop.png)

```blocks3
set [score v] to (0)

when flag clicked
```

![sprite-fantôme](images/ghost-sprite.png)

```blocks3
change [score v] by (1)
```

--- /hint --- --- hint --- ![icône de l'arrière-plan](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [score v] to (0)
```

![sprite-fantôme](images/ghost-sprite.png)

```blocks3
When this sprite clicked
hide
+ change [score v] by (1)
```

--- /hint --- --- /hints ---

--- /task ---