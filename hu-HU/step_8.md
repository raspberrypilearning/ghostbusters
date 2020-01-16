## Időzítő hozzáadása

Most adj hozzá egy időzítőt, hogy a játékosnak csak 10 másodperce legyen a lehető legtöbb szellem összegyűjtésére.

\--- task \---

Hozz létre egy "idő" nevű változót.

\--- /task \---

\--- task \---

Hozzá tudsz adni egy olyan időzítőt a Játéktérhez, hogy a játékosnak csak 10 másodpercet adjon a szellemek elkapására?

Az időzítődnek:

+ 10 másodpercről kell indulnia
+ minden másodpercben vissza kell számolnia

A játéknak le kell állnia, ha az időzítő 0-hoz ér.

\--- hints \--- \--- hint \---

`When the green flag is clicked`{:class="block3events"}, your `time`{:class="block3variables"} variable should be `set to 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need to use:

![szellem-szereplő](images/ghost-backdrop.png)

```blocks3
álljon le [minden feladat]

< [ ] = [ ] >

[idő v] legyen [10]

[idő v] változzon (-1)

(idő)

várj (1) mp-et

ismételd eddig: < >
end

⚑ -ra kattintáskor

```

\--- /hint \--- \--- hint \---

Here is the code you should add to create a timer:

![háttér ikon](images/ghost-backdrop.png)

```blocks3
⚑ -ra kattintáskor
[idő v] legyen [10]
ismételd eddig: < (time) = [0] >
várj (1) mp-et
[idő v] változzon (-1)
end
álljon le [minden feladat]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

If your game is too easy, you can:

+ adj kevesebb időt a játékosnak
+ ritkábban jelenjenek meg a szellemek
+ legyenek kisebbek a szellemek

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---