## おばけをつかまえるコード

ゲームにコードを追加してプレイヤーがおばけをつかまえられるようにしましょう！

--- task ---

おばけがつかまったらきえるようにできますか？プレイヤーはおばけをクリックしてつかまえることができます。

ゲームをテストしておばけをつかまえるのがむずかしければ、このボタンをクリックして全画面モードでゲームをプレイできます。

![スクリーンショット](images/ghost-fullscreen-annotated.png)

--- hints ---
 --- hint ---

`クリックされたとき`{:class="block3events"}、おばけのスプライトは`隠れる`{:class="block3looks"}必要があります。

--- /hint --- --- hint ---

コードは次のようになります:

![おばけのスプライト](images/ghost-sprite.png)

```blocks3
when this sprite clicked
hide
```

--- /hint ------ /hints ---

--- /task ---