## Dodaj rezultat

Napravimo igru još interesantnijom tako što ćemo pratiti rezultat!

\--- task \---

Kreiraj novu promjenljivu pod nazivom 'rezultat'.

[[[generic-scratch-add-variable]]]

\--- /task \---

\--- task \---

Da li možeš da pratiš igračev rezultat? Igrač bi trebalo da dobije bod kada klikne na duha i uhvati ga.

Svaki put kada igrač klikne na duha, njegov rezultat treba da se poveća.

![Increasing score](images/ghost-score-test.png)

\--- hints \--- \--- hint \--- `Kada se klikne na zelenu zastavicu` {:class=”blockevents”} (when the green flag is clicked), tvoja promjenljiva `rezultat`{:class=”blockdata”} treba da bude `postavljena na 0`{:class=”blockdata”} (set to 0). Pozornica je najbolje mjesto za dodavanje ovog kôda. `When the ghost sprite is clicked`{:class=”blockevents”}, the `score`{:class=”blockdata”} should be `changed by 1`{:class=”blockdata”}. \--- /hint \--- \--- hint \--- Here are the code blocks you will need to use: ![screenshot](images/ghost-score-blocks.png) \--- /hint \--- \--- hint \--- Here's how to score points by clicking ghosts: ![screenshot](images/ghost-score-code.png) \--- /hint \--- \--- /hints \---

\--- /task \---