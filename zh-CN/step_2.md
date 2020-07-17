## 制作幽灵动画

\--- task \---

打开一个空白Scratch项目。

[[[generic-scratch3-new-project]]]

\--- /task \---

\--- task \---

添加一个幽灵角色并选择一个合适的舞台背景。

![截图](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

\--- /task \---

\--- task \---

添加代码，当点击绿旗后，你的幽灵就会一直重复不断地出现并消失。

\--- hint \--- \--- hint \---

当`绿旗被点击`{:class="block3events"}时，你的幽灵应当`隐藏`{:class="block3looks"}`一秒`{:class="block3control"}，然后再`出现`{:class="block3looks"}`一秒`{:class="block3control"}。 它需要`一直`:class="block3control"}重复这样。

\--- /hint \--- \--- hint \---

Here are the code blocks you need:

![幽灵角色](images/ghost-sprite.png)

```blocks3
隐藏

显示

重复执行
结束

等待（1）秒

等待（1）秒

当绿旗被点击时
```

\--- /hint \--- \--- hint \---

This is what your code should look like:

![幽灵角色](images/ghost-sprite.png)

```blocks3
当绿旗被点击
重复执行
隐藏
等待（1）秒
显示
等待（1）秒
结束
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Test and save your project.

[[[generic-scratch3-saving]]]

\--- /task \---