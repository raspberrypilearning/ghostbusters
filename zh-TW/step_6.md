## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

你的計時器應該要：

+ 從 10 秒開始計算
+ 每秒倒數

遊戲應該在計時器算到 0 的時候就停止。

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

![背景圖示](images/ghost-backdrop.png)

```blocks3
當 @greenflag 被點擊
變數 [時間 v] 設為 (10)
重複直到 < (時間) = [0] >
等待 (1) 秒
變數 [時間 v] 改變 (-1)
end
停止 [全部 v]
```

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

修改並測試你的遊戲，改到你對遊戲的難度滿意為止。

\--- /task \---