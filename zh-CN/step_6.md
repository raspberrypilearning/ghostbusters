## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

你的倒计时器应当：

+ 初始设置10秒
+ 按秒倒计时

当倒计时器为0时游戏结束。

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
当绿旗被点击
将 [time v] 设为 [10]
重复执行直到 < (time) = [0] >
等待 (1) 秒
将 [time v] 增加 (-1)
结束
停止 [all]
```

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---