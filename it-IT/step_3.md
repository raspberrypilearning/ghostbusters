## Fantasmi a caso

Al momento, è facilissimo acchiappare il tuo fantasma, perché non si muove!

--- task ---

Puoi aggiungere del codice per fare in modo che il tuo fantasma, invece di stare fermo nello stesso punto, compaia sullo schermo in punti a caso?

--- hints ---


--- hint ---

Ogni volta prima che il tuo fantasma appare, dovrebbe `andare`{:class="block3motion"} in una posizione casuale sullo schermo.

--- /hint --- --- hint ---

Ci sono due serie di blocchi di codice che puoi usare. Scegli quello che preferisci.

![sprite del fantasma](images/ghost-sprite.png)

Aggiungi questo set di blocchi allo sprite del fantasma:

```blocks3
raggiungi (posizione a caso v)
```

Oppure aggiungi questo allo sprite:

```blocks3
vai a x: (14) y: (50)

(numero a caso tra (1) e (10))

(numero a caso tra (1) e (10))
```

--- /hint ---

--- hint ---

Il tuo codice ora dovrebbe apparire così:

![sprite del fantasma](images/ghost-sprite.png)

```blocks3
quando si clicca sulla bandiera verde
per sempre 
nascondi
attendi (1) secondi
raggiungi (posizione a caso v)
mostra
attendi (1) secondi
```

Oppure potrebbe apparire così:

![sprite del fantasma](images/ghost-sprite.png)

```blocks3
quando si clicca sulla bandiera verde
per sempre 
nascondi
attendi (1) secondi
vai a x: (numero a caso tra (-150) e (150)) y: (numero a caso tra (-150) e (150))
mostra
attendi (1) secondi
```

--- /hint --- --- /hints ---

--- /task ---