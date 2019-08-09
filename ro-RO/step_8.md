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

\--- hints \--- \--- hint \--- `Când se dă click pe stegulețul verde`{:class="block3events"}, variabila `timp`{:class="block3variables"} va trebui să fie `setată la 10`{:class="block3variables"}. Apoi, ar trebui să se `modifice cu -1`{:class="block3variables"} în fiecare secundă `până când ajunge la 0`{:class="block3control"}. \--- /hint \--- \--- hint \--- Iată blocurile de cod de care ai nevoie: ![fantomă](images/ghost-backdrop.png)

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

\--- /hint \--- \--- hint \--- Iată codul pe care trebuie să îl adaugi pentru a crea un cronometru: ![decor](images/ghost-backdrop.png)

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

Cere-i unui prieten să îți testeze jocul. Câte puncte poate să adune?

\--- /task \---

Dacă jocul e prea ușor, ai putea:

+ Micșora timpul de joc
+ Aranja ca fantomele să apară mai rar
+ Micșora fantomele

\--- task \---

Modifică și testează-ți jocul de mai multe ori până când ești mulțumit de gradul lui de dificultate.

\--- /task \---