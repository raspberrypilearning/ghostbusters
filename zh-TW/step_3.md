## 隨機出現的鬼魂

這些鬼太容易被抓到了，因為它都固定在同一個地方出現！

\--- task \---

Add code to your ghost so that, instead of staying in the same position, the ghost appears at random positions on the Stage:

![幽靈角色](images/ghost-sprite.png)

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