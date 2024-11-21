## Add a timer

Add a timer to your Stage to give your player only 10 seconds to catch ghosts.

Твой таймер должен:

+ Иметь начальное значение в 10 секунд
+ Каждую секунду вести обратный отсчёт

Игра должна прекратиться, когда таймер достигнет значения 0.

\--- task \---

Create a new variable called `time`{:class="block3variables"}.

\--- /task \---

\--- task \---

Add this code to your **Stage**:

![фоновая иконка](images/ghost-backdrop.png)

```blocks3
когда щёлкнут по зелёному флагу
задать [время v] значение [10]
повторять пока не < (время) = [0] >
 ждать (1) секунд
 изменить [время v] на (-1)
end
стоп [все]
```

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

\--- task \---

Изменяй и тестируй свою игру до тех пор, пока ты не будешь доволен уровнем сложности.

\--- /task \---