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

`quando si clicca sulla bandiera verde`{:class=”block3events”}, la tua variabile `tempo`{:class=”block3variables”} dovrebbe `essere impostata a 10`{:class="block3variables"}. Dovrebbe quindi `cambiare di -1`{:class="block3variables"} ogni secondo `fino a quando non raggiunge 0`{:class="block3control"}.

\--- /hint \--- \--- hint \---

Ecco i blocchi di codice che ti serviranno:

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

Ecco il codice che dovresti aggiungere per creare un timer:

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

Chiedi a un amico di provare il tuo gioco. Quanti punti riescono a segnare?

\--- /task \---

Se il gioco è troppo facile, puoi:

+ Dare al giocatore meno tempo
+ Ridurre la frequenza con cui i fantasmi appaiono
+ Rimpicciolire i fantasmi

\--- task \---

Cambia e prova il tuo gioco alcune volte fino a quando non sei soddisfatto del suo livello di difficoltà.

\--- /task \---