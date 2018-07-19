## Dodaj mjerač vremena

\--- task \---

Kreiraj novu promjenljivu pod nazivom 'vrijeme'.

\--- /task \---

\--- task \---

Možeš li da dodaš mjerač vremena na svoju Pozornicu kako bismo tvom igraču dali samo 10 sekundi da uhvati što više duhova?

Tvoj mjerač vremena treba da:

+ Počne sa 10 sekundi
+ Odbrojava svaku sekundu

Igra treba da se završi kada mjerač vremena dođe do 0.

\--- hints \--- \--- hint \--- `Kada se klikne na zelenu zastavicu`{:class=”blockevents”} (when the green flag is clicked), tvoja promjenljiva `vrijeme`{:class=”blockdata”} treba da bude `postavljena na 10`{:class=”blockdata”} (set to 10). Zatim treba svakog sekunda da se `promijeni za -1`{:class=”blockdata”} (change by -1) `dok ne dođe do 0`{:class=”blockcontrol"}. \--- /hint \--- \--- hint \--- Here are the code blocks you will need to use: ![screenshot](images/ghost-timer-blocks.png) \--- /hint \--- \--- hint \--- Here's how to add the timer to your game: ![snimak ekrana](images/ghost-timer-code.png)

And this is how to create the `time = 0` block: ![screenshot](images/ghost-timer-help.png) \--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

If your game is too easy, you can:

+ Give the player less time
+ Make the ghosts appear less often
+ Make the ghosts smaller

\--- task \---

Change and test your game a few times until you're happy that it's the right level of difficulty.

\--- /task \---