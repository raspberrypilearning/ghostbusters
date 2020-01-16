## Adaugă un cronometru

Acum vei adăuga un cronometru pentru ca jucătorul să aibă la dispoziție doar 10 secunde pentru a prinde cât mai multe fantome.

\--- task \---

Creează o variabilă nouă, numită „timp”.

\--- /task \---

\--- task \---

Poți adăuga un cronometru la Scena ta pentru a oferi jucătorului tău doar 10 secunde la dispoziție pentru a prinde fantome?

Cronometrul tău ar trebui:

+ Să înceapă în 10 secunde
+ Să numere înapoi fiecare secundă

Jocul ar trebui să se oprească când timpul ajunge la 0.

\--- hints \--- \--- hint \---

`When the green flag is clicked`{:class="block3events"}, your `time`{:class="block3variables"} variable should be `set to 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need to use:

![fantomă](images/ghost-backdrop.png)

```blocks3
stop [totul]

< [ ] = [ ] >

setează [timp v] la [10]

modifică [timp v] cu (-1)

(timp)

așteaptă (1) secunde

repetă până când < >
end

când se dă click pe stegulețul verde

```

\--- /hint \--- \--- hint \---

Here is the code you should add to create a timer:

![decor](images/ghost-backdrop.png)

```blocks3
când se dă click pe stegulețul verde
setează [timp v] la [10]
repetă până când < (timp) = [0] >
așteaptă (1) secunde
modifică [timp v] cu (-1)
end
stop [totul]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

If your game is too easy, you can:

+ Micșora timpul de joc
+ Aranja ca fantomele să apară mai rar
+ Micșora fantomele

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---