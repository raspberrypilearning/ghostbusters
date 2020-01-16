## 計時開始

現在我們來添加一個計時器，在限時 10 秒內看玩家能抓到多少鬼。

\--- task \---

建立一個名為「時間」的變數。

\--- /task \---

\--- task \---

你可以在舞台裡添加一個計時工具，限定玩家只有 10 秒時間捉鬼嗎？

你的計時器應該要：

+ 從 10 秒開始計算
+ 每秒倒數

遊戲應該在計時器算到 0 的時候就停止。

\--- hints \--- \--- hint \---

`When the green flag is clicked`{:class="block3events"}, your `time`{:class="block3variables"} variable should be `set to 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need to use:

![幽靈角色](images/ghost-backdrop.png)

```blocks3
停止 [全部 v]

< [ ] = [ ] >

變數 [時間 v] 設為 (10)

變數 [時間 v] 改變 (-1)

(時間)

等待 (1) 秒

重複直到 < >
end

當 @greenflag 被點擊

```

\--- /hint \--- \--- hint \---

Here is the code you should add to create a timer:

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

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

If your game is too easy, you can:

+ 給玩家更少的時間
+ 讓鬼出現的頻率降低
+ 把鬼變小一點

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---