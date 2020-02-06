## Fantome la întâmplare

Fantoma ta e ușor de prins acum, deoarece nu se mișcă!

\--- task \---

Poți să adaugi cod la fantoma ta astfel încât, în loc să stea nemișcată, aceasta să apară într-o poziție la întâmplare pe Scenă?

\--- hints \---

\--- hint \---

De fiecare dată când fantoma ta apare, ar trebui să `meargă la`{:class="block3motion"} o poziție la întâmplare pe Scenă.

\--- /hint \--- \--- hint \---

Sunt două seturi de blocuri de cod pe care le-ai putea folosi aici. Alege-l pe cel pe care îl preferi.

![fantomă](images/ghost-sprite.png)

Fie adaugi acest set de blocuri la fantoma ta:

```blocks3
mergi la (poziție aleatoare v)
```

Sau adaugi acesta la personajul tău:

```blocks3
mergi la x: (14) y: (50)

alege aleator între (1) și (10)

alege aleator între (1) și (10)
```

\--- /hint \---

\--- hint \---

Codul tău ar putea să arate astfel:

![ghost-sprite](images/ghost-sprite.png)

```blocks3
când se dă click pe stegulețul verde
la infinit
ascunde
așteaptă (1) secunde
mergi la (poziție aleatoare v)
arată
așteaptă (1) secunde
end
```

Sau ar putea arăta astfel:

![ghost-sprite](images/ghost-sprite.png)

```blocks3
când se dă click pe stegulețul verde
la infinit
ascunde
așteaptă (1) secunde
mergi la x: (alege aleator între (-150) și (150)) y: (alege aleator între (-150) și (150))
arată
așteaptă (1) secunde
end
```

\--- /hint \--- \--- /hints \---

\--- /task \---