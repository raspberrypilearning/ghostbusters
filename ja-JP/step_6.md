## タイマーを追加する

\--- task \---

「時間」という変数を新しく作成します。

\--- /task \---

\--- task \---

プレイヤーがたった10秒以内に、できるだけたくさんのおばけをつかまえられるように、ステージにタイマーを追加できますか？

タイマーはこのようにします。

+ 10秒から始まる
+ 1秒ずつへっていく

タイマーが0になると、ゲームは終わります。

\--- hints \--- \--- hint \--- `グリーンフラッグがクリックされたとき`{:class=”blockevents”}、`時間`{:class=”blockdata”}の変数を`10にする`{:class=”blockdata”}必要があります。 It should then `change by -1`{:class=”blockdata”} every second `until it reaches 0`{:class=”blockcontrol"}. \--- /hint \--- \--- hint \--- Here are the code blocks you will need to use: ![screenshot](images/ghost-timer-blocks.png) \--- /hint \--- \--- hint \--- Here's how to add the timer to your game: ![スクリーンショット](images/ghost-timer-code.png)

And this is how to create the `time = 0` block: ![screenshot](images/ghost-timer-help.png) \--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

If your game is too easy, you can:

+ Give the player less time
+ Make the ghosts appear less often
+ Make the ghosts smaller

\--- task \---

Change and test your game a few times until you're happy that it's the right level of difficulty.

\--- /task \---