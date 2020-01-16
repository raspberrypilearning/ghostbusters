## Aggiungere un timer

Ora aggiungerai un timer in modo che il giocatore abbia solo 10 secondi per catturare il maggior numero di fantasmi.

\--- task \---

Crea una nuova variabile chiamata 'tempo'.

\--- /task \---

\--- task \---

Puoi aggiungere un timer al tuo sfondo per dare al tuo giocatore solo 10 secondi per catturare quanti più fantasmi possibile?

Il tuo timer dovrebbe:

+ Partire da 10 secondi
+ Contare alla rovescia ogni secondo

Il gioco dovrebbe interrompersi quando il timer raggiunge lo 0.

\--- hints \--- \--- hint \---

`When the green flag is clicked`{:class="block3events"}, your `time`{:class="block3variables"} variable should be `set to 10`{:class="block3variables"}. It should then `change by -1`{:class="block3variables"} every second `until it reaches 0`{:class="block3control"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you need to use:

![sprite del fantasma](images/ghost-backdrop.png)

```blocks3
ferma [all]

< [ ] = [ ] >

porta [time v] a [10]

cambia [time v] di (-1)

(time)

attendi (1) secondi

ripeti fino a quando < >
end

quando si clicca sulla bandiera verde

```

\--- /hint \--- \--- hint \---

Here is the code you should add to create a timer:

![icona scenario](images/ghost-backdrop.png)

```blocks3
quando si clicca sulla bandiera verde
porta [time v] a [10]
ripeti fino a quando <(time) = [0]>
attendi (1) secondi
cambia [time v] di (-1)
end
ferma [all]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Ask a friend to test your game. How many points can they score?

\--- /task \---

If your game is too easy, you can:

+ Dare al giocatore meno tempo
+ Ridurre la frequenza con cui i fantasmi appaiono
+ Rimpicciolire i fantasmi

\--- task \---

Change and test your game a few times until you're happy with its level of difficulty.

\--- /task \---