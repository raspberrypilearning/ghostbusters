## Ajouter un minuteur

Tu vas maintenant ajouter une minuterie afin que le joueur ne dispose que de dix secondes pour capturer le plus de fantômes possible.

--- task ---

Créer une nouvelle variable appelée « temps ».

--- /task ---

--- task ---

Peux-tu ajouter une minuterie à ta scène pour donner à ton joueur seulement 10 secondes pour attraper les fantômes?

Ton chronomètre devrait:

+ Commencer à 10 secondes
+ Compter à rebours toutes les secondes

Le jeu devrait s'arrêter quand le chronomètre atteindra 0.

--- hints ---
 --- hint --- `Lorsque le drapeau vert est cliqué`{:class="block3events"}, ta variable `temps`{:class="block3variables"} devrait être `définie à 10`{:class="block3variables"}. Il devrait alors `diminuer de 1`{:class="block3variables"} toutes les secondes `jusqu'à ce qu'il atteigne 0`{:class="block3control"}. --- /hint --- --- hint --- Voici les blocs de code que tu dois utiliser: ![sprite-fantôme](images/ghost-backdrop.png)

```blocks3
stop [tout]

< [] = [] >

set [temps v] to [10]

change [temps v] by (-1)

(temps)

wait (1) seconds

repeat until < >
end

when flag clicked

```

--- /hint --- --- hint --- Voici le code que tu dois ajouter pour créer une minuterie: ![icône de l'arrière-plan](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [temps v] to [10]
repeat until < (temps) = [0] >
wait (1) seconds
change [temps v] by (-1)
end
stop [tout]
```

--- /hint --- --- /hints ---

--- /task ---

--- task ---

Demande à un ami de tester ton jeu. Combien de points peuvent-ils marquer?

--- /task ---

Si ton jeu est trop facile, tu peux:

+ Donner au joueur moins de temps
+ Faire apparaître les fantômes moins souvent
+ Rendre les fantômes plus petits

--- task ---

Change et teste ton jeu plusieurs fois jusqu'à ce que tu sois satisfait de son niveau de difficulté.

--- /task ---
