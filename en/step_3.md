## Random ghosts

Your ghost is really easy to catch at the moment, because it doesn't move!

--- task ---

Can you add code to your ghost so that, instead of staying in the same position, the ghost appears at random positions on the Stage?

--- hints ---

--- hint ---

Each time before your ghost appears, it should `go to`{:class="blockmotion"} a random position on the Stage.

--- /hint ---
--- hint ---

There are two sets of code blocks you could use here. Choose the set you prefer.

![ghost-sprite](images/ghost-sprite.png)

Either add this set of blocks to your ghost sprite:

``` blocks
go to (random position)
```
Or add this one to your sprite:

``` blocks
go to x: (14) y: (50)

pick random (1) to (10)

pick random (1) to (10)
```

--- /hint ---

--- hint ---

Your code could look either like this:

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

Or it could look like this:

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
