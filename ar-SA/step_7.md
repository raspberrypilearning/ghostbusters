## التحدي: كائنات أخرى

Now you're going to make your game more interesting by keeping score!

\--- task \---

Create a new variable called `score`{:class="block3variables"}.

[[[generic-scratch3-add-variable]]]

\---/task--

\--- task \---

Can you keep track of the player's score? Players should score points when they click on ghosts to catch them.

في كل مرة ينقر فيها اللاعب على الشبح، يجب ان تزيد عدد النقاط.

![زيادة النقاط](images/ghost-score-test.png)

\--- hints \--- \--- hint \---

`When the green flag is clicked`{:class="block3events"}, your `score`{:class="block3variables"} variable should be `set to 0`{:class="block3variables"}. المنصة هي أفضل مكان لإضافة هذه التعليمة البرمجية.

`When the ghost sprite is clicked`{:class="block3events"}, the `score`{:class="block3variables"} variable should be `changed by 1`{:class="block3variables"}.

\--- /hint \--- \--- hint \--- Here are the code blocks you need: ![backdrop icon](images/ghost-backdrop.png)

```blocks3
set [score v] to (0)

when flag clicked
```

![ghost-sprite](images/ghost-sprite.png)

```blocks3
غيِّر [score v] بمقدار (1)
```

\--- /hint \--- \--- hint \--- ![backdrop icon](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [score v] to (0)
```

![ghost-sprite](images/ghost-sprite.png)

```blocks3
When this sprite clicked
hide

+ change [score v] by (1)
```

\--- /hint \--- \--- /hints \---

\--- /task \---