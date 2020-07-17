## Adj hozzá eredményszámolálót

Tedd érdekesebbé a játékot az elkapott szellemek számolásával!

\--- task \---

Hozz létre egy új változót, amelynek a neve legyen `eredmény`{:class="block3variables"}.

[[[generic-scratch3-add-variable]]]

\--- /task \---

\--- task \---

Nyomon tudod követni a játékos pontszámát? A játékosoknak pontokat kell kapniuk, amikor rákattintanak a szellemekre.

Minden alkalommal, amikor a játékos rákattint egy szellemre, a pontszámnak növekednie kell.

![Az eredmény növelése](images/ghost-score-test.png)

\--- hints \--- \--- hint \---

`Ha a zöld zászlóra`{:class="block3events"} rákattintanak, akkor az `eredmény`{:class="block3variables"} értéke `változzon 0-ra`{:class="block3variables"}. A Játéktérhez add hozzá a következő kódot.

`A szellem szereplőre rákattintáskor`{:class="block3events"}, az `eredmény`{:class="block3variables"} értéke `változzon 1-gyel`{:class="block3variables"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need:

![háttér ikon](images/ghost-backdrop.png)

```blocks3
[eredmény v] legyen (0)

⚑ -ra kattintáskor
```

![szellem-szereplő](images/ghost-sprite.png)

```blocks3
[eredmény v] változzon (1)
```

\--- /hint \--- \--- hint \---

![háttér ikon](images/ghost-backdrop.png)

```blocks3
⚑ -ra kattintáskor
[eredmény v] legyen (0)
```

![szellem-szereplő](images/ghost-sprite.png)

```blocks3
ezen szereplőre kattintáskor
tűnj el

[eredmény v] változzon (1)
```

\--- /hint \--- \--- /hints \---

\--- /task \---