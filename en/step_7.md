## Add a score

Now you're going to make your game more interesting by keeping score!

--- task ---

Create a new variable called `score`.

[[[generic-scratch-add-variable]]]

--- /task ---

--- task ---

Can you keep track of the player's score? Players should score points when they click on ghosts to catch them.

Each time a player clicks on a ghost, their score should increase.

![Increasing score](images/ghost-score-test.png)

--- hints ---
--- hint ---

`When the green flag is clicked`{:class="blockevents"}, your `score`{:class="blockdata"} variable should be `set to 0`{:class="blockdata"}. The Stage is the best place to add this code.

`When the ghost sprite is clicked`{:class="blockevents"}, the `score`{:class="blockdata"} variable should be `changed by 1`{:class="blockdata"}.

--- /hint ---
--- hint ---
Here are the code blocks you need:
![backdrop icon](images/ghost-backdrop.png)
``` blocks
set [score] to (0)

when flag clicked
```

![ghost-sprite](images/ghost-sprite.png)
``` blocks
change [score] by (1)
```
--- /hint ---
--- hint ---
![backdrop icon](images/ghost-backdrop.png)

``` blocks
when flag clicked
set [score] to (0)
```
![ghost-sprite](images/ghost-sprite.png)
``` blocks
When this sprite clicked
hide
play sound [pop]
+ change [score] by (1)
```
--- /hint ---
--- /hints ---

--- /task ---
