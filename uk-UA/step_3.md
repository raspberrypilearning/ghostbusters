## Випадкові привиди

Твого привида зараз дуже легко зловити, оскільки він не рухається!

\--- task \---

Add code to your ghost so that, instead of staying in the same position, the ghost appears at random positions on the Stage:

![спрайт привида](images/ghost-sprite.png)

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