## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

Твій таймер має:

+ Починатися з 10 секунд
+ Зменшуватися кожну секунду

Гра має зупинитись, коли таймер дійде до 0.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

![значок тла](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [time v] to [10]
repeat until < (time) = [0] >
wait (1) seconds
change [time v] by (-1)
end
stop [all]
```

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

Зміни та протестуй свою гру декілька разів, поки не будеш задоволений її рівнем складності.

\--- /task \---