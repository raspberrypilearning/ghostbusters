## Випадкові привиди

Твого привида зараз дуже легко зловити, оскільки він не рухається!

\--- task \---

Чи можеш ти додати код до свого привида так, щоб він з’являвся на Сцені у випадкових місцях замість того, щоб залишатися на місці?

\--- hints \---

\--- hint \---

Кожного разу, перш ніж твій привид з’явиться, він повинен `перейти до`{:class="block3motion"} випадкового положення на Сцені.

\--- /hint \--- \--- hint \---

Є два набори блоків коду, які ти можеш використати. Вибирай той, який більше подобається.

![спрайт привида](images/ghost-sprite.png)

Додай або цей набір блоків до свого спрайту привида:

```blocks3
go to (random position v)
```

Або цей:

```blocks3
go to x: (14) y: (50)

pick random (1) to (10)

pick random (1) to (10)
```

\--- /hint \---

\--- hint \---

Твій код може виглядати так:

![спрайт привида](images/ghost-sprite.png)

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

Або так:

![спрайт привида](images/ghost-sprite.png)

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

\--- /hint \--- \--- /hints \---

\--- /task \---