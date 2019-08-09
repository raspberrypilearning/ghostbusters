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

\--- hints \--- \--- hint \--- `Amikor a zöld zászlóra rákattintanak`{:class="block3events"}, az `idő`{:class="block3variables"} változót `10-re kell állítani`{:class="block3variables"}. Aztán `-1-gyel kell változnia`{:class="block3variables"} minden másodpercben, `amíg eléri a 0-t`{:class="block3control"}. \--- /hint \--- \--- hint \--- Íme a szükséges kódblokkok: ![szellem-szereplő](images/ghost-backdrop.png)

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

\--- /hint \--- \--- hint \--- Ez az időzítőhöz szükséges kód: ![háttér ikon](images/ghost-backdrop.png)

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

Kérd meg egy barátod, hogy tesztelje a játékod. Mennyi pontot szerezhetnek?

\--- /task \---

Ha a játék túl könnyű, akkor:

+ adj kevesebb időt a játékosnak
+ ritkábban jelenjenek meg a szellemek
+ legyenek kisebbek a szellemek

\--- task \---

Módosítsd és próbáld ki a játékod néhányszor, amíg elégedett leszel a nehézségi szintjével.

\--- /task \---