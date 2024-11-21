## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

Ton chronomètre devrait:

+ Commencer à 10 secondes
+ Compter à rebours toutes les secondes

Le jeu devrait s'arrêter quand le chronomètre atteindra 0.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

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

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

Change et teste ton jeu plusieurs fois jusqu'à ce que tu sois satisfait de son niveau de difficulté.

\--- /task \---