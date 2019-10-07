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

mettre [temps v] à [10]

ajouter (-1) à [temps v]

temps :: variables

attendre (1) secondes

répéter jusqu'à ce que < >
fin

quand le drapeau vert pressé

```

--- /hint --- --- hint --- Voici le code que tu dois ajouter pour créer une minuterie: ![icône de l'arrière-plan](images/ghost-backdrop.png)

```blocks3
quand le drapeau vert pressé
mettre [temps v] à [10]
répéter jusqu'à ce que < (temps :: variables) = [0] > 
attendre (1) secondes
ajouter (-1) à [temps v]
fin
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
