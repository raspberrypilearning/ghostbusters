## Dodavanje rezultata

Napravimo igru zanimljivijom tako što ćemo dodati rezultat!

\--- task \---

Stvori novu varijablu 'rezultat'.

[[[generic-scratch-add-variable]]]

\--- /task \---

\--- task \---

Možeš li pratiti igračev rezultat? Igrači dobivaju bodove kada kliknu na duhove i uhvate ih.

Svaki put kad igrač klikne na duha, njegov rezultat se treba povećati.

![Increasing score](images/ghost-score-test.png)

\--- hints \--- \--- hint \--- `When the green flag is clicked`{:class=”blockevents”}, your `score`{:class=”blockdata”} variable should be `set to 0`{:class=”blockdata”}. The Stage is the best place to add this code. `When the ghost sprite is clicked`{:class=”blockevents”}, the `score`{:class=”blockdata”} should be `changed by 1`{:class=”blockdata”}. \--- /hint \--- \--- hint \--- Here are the code blocks you will need to use: ![screenshot](images/ghost-score-blocks.png) \--- /hint \--- \--- hint \--- Here's how to score points by clicking ghosts: ![screenshot](images/ghost-score-code.png) \--- /hint \--- \--- /hints \---

\--- /task \---