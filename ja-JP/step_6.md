## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

タイマーはこのようにします。

+ 10秒から開始
+ 1秒ずつへっていく

タイマーが0になると、ゲームは終わります。

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

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

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

まんぞくできるむずかしさになるまで、ゲームを変えてテストしましょう。

\--- /task \---