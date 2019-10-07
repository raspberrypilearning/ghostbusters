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
mettre [score v] à (0)

quand le drapeau vert pressé
```

![sprite-fantôme](images/ghost-sprite.png)

```blocks3
ajouter (1) à [score v]
```

--- /hint --- --- hint --- ![icône de l'arrière-plan](images/ghost-backdrop.png)

```blocks3
quand le drapeau vert pressé
mettre [score v] à (0)
```

![sprite-fantôme](images/ghost-sprite.png)

```blocks3
quand ce sprite est cliqué
cacher
+ ajouter (1) à [score v]
```

--- /hint --- --- /hints ---

--- /task ---