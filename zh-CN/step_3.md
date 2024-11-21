## 随机幽灵

目前你的幽灵实在是太容易被抓住了，因为它不会移动！

\--- task \---

Add code to your ghost so that, instead of staying in the same position, the ghost appears at random positions on the Stage:

![幽灵角色](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
+go to (random position v)
show
wait (1) seconds
end
```

\--- /task \---

\--- task \---

Test your code. Click the green flag. Your ghost should appear in random places.

\--- /task \---