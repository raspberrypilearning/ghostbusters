## Fantasmi a caso

Al momento, è facilissimo acchiappare il tuo fantasma, perché non si muove!

\--- task \---

Puoi aggiungere del codice per fare in modo che il tuo fantasma, invece di stare fermo nello stesso punto, compaia sullo schermo in punti a caso?

\--- hints \---

\--- hint \---

Ogni volta prima che il tuo fantasma appare, dovrebbe `andare`{:class="block3motion"} in una posizione casuale sullo schermo.

\--- /hint \--- \--- hint \---

Ci sono due serie di blocchi di codice che puoi usare. Scegli quello che preferisci.

![sprite del fantasma](images/ghost-sprite.png)

Aggiungi questo set di blocchi allo sprite del fantasma:

```blocks3
raggiungi (random position v)
```

Oppure aggiungi questo allo sprite:

```blocks3
go to x: (14) y: (50)

pick random (1) to (10)

pick random (1) to (10)
```

\--- /hint \---

\--- hint \---

Il tuo codice ora dovrebbe apparire così:

![ghost-sprite](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to (random position v)
show
wait (1) seconds
end
```

Oppure potrebbe apparire così:

![ghost-sprite](images/ghost-sprite.png)

```blocks3
when flag clicked
forever
hide
wait (1) seconds
go to x: (pick random (-150) to (150)) y: (pick random (-150) to (150))
show
wait (1) seconds
end
```

\--- /hint \--- \--- /hints \---

\--- /task \---