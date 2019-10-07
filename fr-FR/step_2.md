## Animer un fantôme

--- task ---

Ouvre un nouveau projet Scratch vide.

[[[generic-scratch3-new-project]]]

--- /task ---

--- task ---

Ajoute un nouveau sprite fantôme et un arrière-plan de scène appropriée.

![capture d'écran](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

--- /task ---

--- task ---

Ajoute du code à ton sprite fantôme afin que celui-ci apparaisse et disparaisse à tout jamais lorsque tu cliques sur le drapeau vert.

--- hints ---
 --- hint ---

Une fois que le `drapeau vert est cliqué`{:class="block3events"}, ton fantôme devrait `se cacher`{:class="block3looks"} pendant `une seconde`{:class="block3control"} puis `se montrer`{:class="block3looks"} pendant `une seconde`{:class="block3control"}. Il doit faire cela `pour toujours`{:class="block3control"}.
--- /hint ---
 --- hint ---

Voici les blocs de code dont tu as besoin: ![sprite-fantôme](images/ghost-sprite.png)

```blocks3
cacher

montrer

répéter indéfiniment
fin

attendre (1) secondes

attendre (1) secondes

quand le drapeau vert pressé
```

--- /hint --- --- hint --- Voici a quoi devrait ressembler ton code: ![sprite-fantôme](images/ghost-sprite.png)

```blocks3
quand le drapeau vert pressé
répéter indéfiniment
cacher
attendre (1) secondes
montrer
attendre (1) secondes
fin
```

--- /hint --- --- /hints ---

--- /task ---

--- task ---

Teste et sauvegarde ton projet.

[[[generic-scratch-saving]]]

--- /task ---