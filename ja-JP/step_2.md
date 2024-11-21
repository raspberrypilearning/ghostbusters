## おばけを動かす

\--- task \---

Open a new empty Scratch project by [clicking here](https://scratch.mit.edu/projects/editor/).

\--- /task \---

\--- task \---

Delete the cat sprite by clicking on the bin icon over the sprite thumbnail. ![The image depicts a thumbnail in the Scratch programming interface. It shows the orange Scratch Cat mascot, which is the default sprite for Scratch projects, displayed in a purple-bordered square labeled "Sprite1." There is also a trash can icon with a white "X" in the top-right corner of the thumbnail, indicating the option to delete the sprite.](images/scratch-thumbnail.png)

\--- /task \---

\--- task \---

新しくおばけのスプライトと、ふさわしい背景（はいけい）を追加します。

![The image depicts a stylized blue ghost-like character with spots, standing in a dark, eerie forest. The forest features leafless trees with slender, bare branches and a purple and black background, suggesting a nighttime setting. The moon is partially visible in the top-left corner, adding to the spooky atmosphere.](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

\--- /task \---

\--- task \---

緑の旗 (はた) がクリックされたときに、ずっとおばけが出てきたりきえたりするようにスプライトにコードを入れましょう。

![The image shows a small, cartoonish blue ghost-like figure with rounded edges and a translucent appearance. It has a single, large, black mouth on its left side, a few darker blue spots scattered across its body, and a dripping effect at the bottom, giving it a liquid-like texture.](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
show
wait (1) seconds
end
```

\--- /task \---

\--- task \---

Test and save your project. You should see the ghost appear and disappear when you click the green flag.

[[[generic-scratch3-saving]]]

\--- /task \---