## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

Your timer should:

+ Start at 10 seconds
+ Count down every second

The game should stop when the timer gets to 0.


--- task ---

Create a new variable called 'time'.

--- /task ---

--- task ---

Add this code to your **Stage**:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [time v] to [10]
repeat until < (time) = [0] >
wait (1) seconds
change [time v] by (-1)
end
stop [all]
```

--- /task ---

--- task ---

Ask a friend to test your game. How many points can they score?

--- /task ---

--- task ---

Change and test your game a few times until you're happy with its level of difficulty.

--- /task ---
