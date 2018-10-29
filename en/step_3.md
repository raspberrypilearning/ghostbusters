## Random ghosts

Your ghost is really easy to catch at the moment, because it doesn't move!

--- task ---

Can you add code to your ghost so that, instead of staying in the same position, it appears at random positions on the screen?

--- hints ---
--- hint ---
You want your ghost to `go to`{:class="blockmotion"} a random position on the stage before appearing each time.
--- /hint ---
--- hint ---
There are two sets of code blocks you can use.
This one:
![ghost-sprite](images/ghost-sprite.png)
``` blocks
go to (random position)
```
Or this one:
![ghost-sprite](images/ghost-sprite.png)
``` blocks
go to x: (14) y: (50)

pick random (1) to (10)

pick random (1) to (10)
```
--- /hint ---
--- hint ---
Your code should look either like this:
![ghost-sprite](images/ghost-sprite.png)
``` blocks
when flag clicked
forever
hide
wait 1 secs
go to (random position)
show
wait (1) secs
```
Or it can look like this:
![ghost-sprite](images/ghost-sprite.png)
``` blocks
when flag clicked
forever
hide
wait (1) secs
goto x: (pick random (-150) to (150)) y: (pick random (-150) to (150))
show
wait (1) secs
```
--- /hint ---
--- /hints ---

--- /task ---
