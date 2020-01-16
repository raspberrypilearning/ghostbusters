## Анимация приведения

\--- task \---

Открой новый пустой проект Scratch.

[[[generic-scratch3-new-project]]]

\--- /task \---

\--- task \---

Добавь новый спрайт приведение и подходящий фон для Сцены.

![screenshot](images/ghost-ghost.png)

[[[generic-scratch3-sprite-from-library]]]

[[[generic-scratch3-backdrop-from-library]]]

\--- /task \---

\--- task \---

Добавь код к своему спрайту приведение, чтобы приведение появлялось и исчезало всё время, когда нажат зелёный флаг.

\--- hints \--- \--- hint \---

Когда `зелёный флаг нажат`{:class=”blockevents”}, твоё приведение должно `спрятаться`{:class=”blocklooks”} на `одну секунду`{:class=”blockcontrol”}, а затем `показаться`{:class=”blocklooks”} на `одну секунду`{:class=”blockcontrol”}<0>. Это нужно выполнять `всегда`{:class=”blockcontrol"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need:

![ghost-sprite](images/ghost-sprite.png)

```blocks3
спрятаться

показаться

повторять всегда
end

ждать (1) секунд

ждать (1) секунд

когда щёлкнут по зелёному флагу
```

\--- /hint \--- \--- hint \---

This is what your code should look like:

![ghost-sprite](images/ghost-sprite.png)

```blocks3
когда щёлкнут по зелёному флагу
повторять всегда 
 спрятаться
 ждать (1) секунд
 показаться
 ждать (1) секунд
end
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Test and save your project.

[[[generic-scratch3-saving]]]

\--- /task \---