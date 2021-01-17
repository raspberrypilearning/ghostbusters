## タイマーを追加する

次にタイマーを追加して、プレイヤーが10秒間で出来るだけ多くのおばけをつかまえなければならないようにします。

\--- task \---

'時間'という変数を新しく作成します。

\--- /task \---

\--- task \---

ステージにタイマーを追加して、プレイヤーが10秒間のみおばけをつかまえられるようにできますか？

タイマーはこのようにします。

+ 10秒から開始
+ 1秒ずつへっていく

タイマーが0になると、ゲームは終わります。

\--- hints \--- \--- hint \---

`緑の旗が押されたとき`{:class=”block3events”}、`タイム`{:class=”block3variables”}変数が`10になる`{:class=”block3variables”}必要があります。 それが毎秒`-1ずつ変わり`{:class=”block3variables”}、`0になるまで繰(く)り返される`{:class=”block3control"} 必要があります。

\--- /hint \--- \--- hint \---

必要なコードブロックは次のとおりです。

![おばけのスプライト](images/ghost-backdrop.png)

```blocks3
stop [all]

< [ ] = [ ] >

set [time v] to [10]

change [time v] by (-1)

(time)

wait (1) seconds

repeat until < >
end

when flag clicked

```

\--- /hint \--- \--- hint \---

タイマーを作るのに必要コードは次のとおりです。

![背景 (はいけい) のアイコン](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [time v] to [10]
repeat until < (time) = [0] >
wait (1) seconds
change [time v] by (-1)
end
stop [all]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

友だちにゲームを遊んでもらいましょう。 何点取れましたか？

\--- /task \---

ゲームがかんたんすぎるようでしたら、こんな風にしてみましょう。

+ 時間を短くする
+ おばけをあらわれにくくする
+ おばけを小さくする

\--- task \---

まんぞくできるむずかしさになるまで、ゲームを変えてテストしましょう。

\--- /task \---