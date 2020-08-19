## Случайные призраки

Сейчас твоё приведение очень легко поймать, потому что оно не двигается!

--- task ---

Можешь ли ты добавить к своему приведению код, который бы позволил ему появляться в случайных местах экрана, а не стоять на месте?

--- hints ---


--- hint ---

Каждый раз перед тем, как приведение появляется, оно должно `перейти в`{:class="block3motion"} случайное положение на Сцене.

--- /hint --- --- hint ---

Есть два набора блоков кода, которые ты можешь использовать. Выбери набор, который тебе нравится.

![спрайт-приведение](images/ghost-sprite.png)

Или добавь этот набор блоков к своему приведению:

```blocks3
go to (random position v)
```

Или добавь это в свой спрайт:

```blocks3
go to x: (14) y: (50)

pick random (1) to (10)

pick random (1) to (10)
```

--- /hint ---

--- hint ---

Твой код может выглядеть, как этот:

![спрайт-приведение](images/ghost-sprite.png)

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

Или он может выглядеть, как этот:

![спрайт-приведение](images/ghost-sprite.png)

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