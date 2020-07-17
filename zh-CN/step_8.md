## 添加倒计时

现在你需要添加一个倒计时器，使玩家在只有10秒钟的时间内抓住尽可能多的幽灵。

\--- task \---

新建一个叫“time”的变量。

\--- /task \---

\--- task \---

你能在舞台上添加一个倒计时器以只给玩家10秒的时间来抓幽灵吗？

你的倒计时器应当：

+ 初始设置10秒
+ 按秒倒计时

当倒计时器为0时游戏结束。

\--- hint \--- \--- hint \---

`When the green flag is clicked`{:class="block3events"}, your `time`{:class="block3variables"} variable should be `set to 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need to use:

![幽灵角色](images/ghost-backdrop.png)

```blocks3
停止 [all]

< [ ] = [ ] >

将 [time v] 设为 [10]

将 [time v] 增加 (-1)

(time)

等待 (1) 秒

重复执行直到 < >
结束

当绿旗被点击

```

\--- /hint \--- \--- hint \---

Here is the code you should add to create a timer:

![背景图标](images/ghost-backdrop.png)

```blocks3
当绿旗被点击
将 [time v] 设为 [10]
重复执行直到 < (time) = [0] >
等待 (1) 秒
将 [time v] 增加 (-1)
结束
停止 [all]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

If your game is too easy, you can:

+ 给玩家更少的时间
+ 减少幽灵的出现频率
+ 让幽灵变小点

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---