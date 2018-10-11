## Adding a timer

--- task ---

Create a new variable called 'time'.

--- /task ---

--- task ---

Can you add a timer to your Stage to give your player only 10 seconds to catch as many ghosts as possible?

Your timer should:

+ Start at 10 seconds
+ Count down every second

The game should stop when the timer gets to 0.

--- hints ---
--- hint ---
`When the green flag is clicked`{:class=”blockevents”}, your `time`{:class=”blockdata”} variable should be `set to 10`{:class=”blockdata”}. It should then `change by -1`{:class=”blockdata”} every second `until it reaches 0`{:class=”blockcontrol"}.
--- /hint ---
--- hint ---
Here are the code blocks you will need to use:
![ghost-sprite](images/ghost-resize.png)
``` blocks
stop [all]

< [ ] = [ ] >

set [time] to [10]

change [time] by (-1)

time

wait (1) secs

repeat until < >

when flag clicked

```
--- /hint ---
--- hint ---
Here's how to add the timer to your game:
![ghost-sprite](images/ghost-resize.png)
``` blocks
when flag clicked
set [time] to [10]
repeat until < (time) = [0] >
wait (1) secs
change [time] by (-1)
stop [all]
```

And this is how to create the `time = 0` block:
![ghost-sprite](images/ghost-resize.png)
``` blocks
when flag clicked
set [time] to 10
repeat until < [(time)] = [0] >
```
--- /hint ---
--- /hints ---

--- /task ---

--- task ---

Ask a friend to test your game. How many points can they score?

--- /task ---

If your game is too easy, you can:

+ Give the player less time
+ Make the ghosts appear less often
+ Make the ghosts smaller

--- task ---

Change and test your game a few times until you're happy that it's the right level of difficulty.

--- /task ---
