## Add a score

Now you're going to make your game more interesting by keeping score!

--- task ---

Create a new variable called `score`{:class="block3variables"}.

[[[generic-scratch3-add-variable]]]

--- /task ---

Keep track of the player's score. Each time a player clicks on a ghost, their score should increase.

![Increasing score](images/ghost-score-test.png)

--- task ---

Add this code to your ghost sprite:

![ghost-sprite](images/ghost-sprite.png)

```blocks3
When this sprite clicked
hide
+change [score v] by (1)
```

--- /task ---

--- task ---

Test your code. When you click the ghost, it should disappear and the score should change by 1.

--- /task ---

--- task ---

Add code to your ghost so that the score resets when a new game starts:

![ghost-sprite](images/ghost-sprite.png)

```blocks3
when flag clicked
+set [score v] to (0)
forever
hide
wait (1) seconds
go to (random position v)
show
wait (1) seconds
end
```

--- /task ---
