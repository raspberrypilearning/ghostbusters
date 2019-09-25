## Aggiungere un punteggio

Ora renderai il tuo gioco più interessante aggiungendo il punteggio!

\--- task \---

Crea una nuova variabile chiamata `punteggio`{:class="block3variables"}.

[[[generic-scratch3-add-variable]]]

\--- /task \---

\--- task \---

Puoi tenere traccia del punteggio del giocatore? I giocatori dovrebbero guadagnare punti facendo click sui fantasmi per catturarli.

Ogni volta che un giocatore fa click su un fantasma, il punteggio dovrebbe aumentare.

![Aumentare il punteggio](images/ghost-score-test.png)

\--- hints \--- \--- hint \---

`Quando si clicca sulla bandierina verde`{:class=”block3events”}, la tua variabile `punteggio`{:class=”block3variables”} dovrebbe `essere azzerata`{:class="block3variables"}. Lo sfondo è il posto più adatto dove inserire questo codice.

`Quando l'immagine del fantasma è cliccata`{:class=”block3events”}, la tua variabile `punteggio`{:class=”block3variables”} dovrebbe `essere aumentata di 1`{:class="block3variables"}.

\--- /hint \--- \--- hint \--- Qui ci sono i blocchi di codice che ti serviranno: ![icona scenario](images/ghost-backdrop.png)

```blocks3
set [score v] to (0)
```

![sprite del fantasma](images/ghost-sprite.png)

```blocks3
cambia [punteggio v] di (1)
```

\--- /hint \--- \--- hint \--- ![icona scenario](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [score v] to (0)
```

![sprite del fantasma](images/ghost-sprite.png)

```blocks3
Quando si clicca questo sprite
nascondi

+ cambia [score v] di (1)
```

\--- /hint \--- \--- /hints \---

\--- /task \---