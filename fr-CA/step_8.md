## Ajouter un minuteur

Tu vas maintenant ajouter une minuterie afin que le joueur ne dispose que de dix secondes pour capturer le plus de fantômes possible.

\--- task \---

Créer une nouvelle variable appelée « temps ».

\--- /task \---

\--- task \---

Peux-tu ajouter une minuterie à ta scène pour donner à ton joueur seulement 10 secondes pour attraper les fantômes?

Ton chronomètre devrait:

+ Commencer à 10 secondes
+ Compter à rebours toutes les secondes

Le jeu devrait s'arrêter quand le chronomètre atteindra 0.

\--- hints \--- \--- hint \---

`When the green flag is clicked`{:class="block3events"}, your `time`{:class="block3variables"} variable should be `set to 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need to use:

![sprite-fantôme](images/ghost-backdrop.png)

```blocks3
stop [all]

< [] = [] >

mettre [temps v] à [10]

ajouter (-1) à [temps v]

(temps)

attendre (1) secondes

répéter jusqu'à ce que < >
fin

lorsque le drapeau est cliqué

```

\--- /hint \--- \--- hint \---

Here is the code you should add to create a timer:

![icône de l'arrière-plan](images/ghost-backdrop.png)

```blocks3
lorsque le drapeau est cliqué
mettre [heure v] à [10]
répéter jusqu'à ce que < (temps) = [0] >
attendre (1) secondes
ajouter (-1) à [temps v]
fin
stop [all]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

If your game is too easy, you can:

+ Donner au joueur moins de temps
+ Faire apparaître les fantômes moins souvent
+ Rendre les fantômes plus petits

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---