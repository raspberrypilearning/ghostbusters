## Add a score

Rwyt ti am wneud y gêm yn fwy diddorol trwy gadw sgôr!

\--- task \---

Creu newidyn newydd o'r enw `sgôr`{:class="block3variables"}.

[[[generic-scratch3-add-variable]]]

\--- /task \---

Keep track of the player's score. Each time a player clicks on a ghost, their score should increase.

![Sgôr cynyddol](images/ghost-score-test.png)

\--- task \---

Add this code to your ghost sprite:

![corlun-ysbryd](images/ghost-sprite.png)

```blocks3
When this sprite clicked
hide
+change [score v] by (1)
```

\--- /task \---

\--- task \---

Test your code. When you click the ghost, it should disappear and the score should change by 1.

\--- /task \---

\--- task \---

Add code to your ghost so that the score resets when a new game starts:

![corlun-ysbryd](images/ghost-sprite.png)

```blocks3
when flag clicked
+set [score v] to (0)
forever
hide
wait (1) seconds
go to (random position v)
show
wait (1) seconds
end
```

\--- /task \---