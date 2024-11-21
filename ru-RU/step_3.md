## Случайные призраки

Сейчас твоё приведение очень легко поймать, потому что оно не двигается!

\--- task \---

Add code to your ghost so that, instead of staying in the same position, the ghost appears at random positions on the Stage:

![спрайт-приведение](images/ghost-sprite.png)

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