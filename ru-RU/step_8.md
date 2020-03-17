## Добавление таймера

А сейчас ты добавишь таймер, чтобы у игрока было всего десять секунд, чтобы поймать как можно больше приведений.

\--- task \---

Создай новую переменную с именем 'время'.

\--- /task \---

\--- task \---

Можешь ли ты добавить на свою Сцену таймер, чтобы дать игроку всего 10 секунд на то, чтобы поймать как можно больше приведений?

Твой таймер должен:

+ Иметь начальное значение в 10 секунд
+ Каждую секунду вести обратный отсчёт

Игра должна прекратиться, когда таймер достигнет значения 0.

\--- hints \--- \--- hint \---

`Когда зелёный флаг нажат`{:class="block3events"}, твоей переменной `время`{:class="block3variables"} должно быть `задано значение 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need to use:

![ghost-sprite](images/ghost-backdrop.png)

```blocks3
stop [all]

< [ ] = [ ] >

set [time v] to [10]

change [time v] by (-1)

(time)

wait (1) seconds

repeat until < >
end

when flag clicked

```

\--- /hint \--- \--- hint \---

Here is the code you should add to create a timer:

![backdrop icon](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [time v] to [10]
repeat until < (time) = [0] >
wait (1) seconds
change [time v] by (-1)
end
stop [all]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

If your game is too easy, you can:

+ Give the player less time
+ Make the ghosts appear less often
+ Make the ghosts smaller

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---