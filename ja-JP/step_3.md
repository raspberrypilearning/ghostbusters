## おばけをランダムに動かす

今おばけは動かないので、とてもつかまえやすいです！

--- task ---

同じ場所にいるのではなく、画面上でランダムにあらわれるよう、おばけにコードを入れてみましょう。

--- hints ---


--- hint ---

おばけは出てくるたびに、 ステージ上のランダムな場所へ`行く`{:class="block3motion"}必要があります。

--- /hint --- --- hint ---

ここで使用できるコードブロックは2通りあります。好きな方をえらんでください。

![おばけのスプライト](images/ghost-sprite.png)

おばけのスプライトにこのブロックを追加します。

```blocks3
(どこかの場所 v) へ行く
```

もしくはこのコードをスプライトに追加します。

```blocks3
go to x: (14) y: (50)

pick random (1) to (10)

pick random (1) to (10)
```

--- /hint ---

--- hint ---

コードは次のようになります：

![おばけのスプライト](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to (random position v)
show
wait (1) seconds
end
```

もしくはこのようになります：

![おばけのスプライト](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to x: (pick random (-150) to (150)) y: (pick random (-150) to (150))
show
wait (1) seconds
end
```

--- /hint ------ /hints ---

--- /task ---