## Aggiungere un timer

Ora aggiungerai un timer in modo che il giocatore abbia solo 10 secondi per catturare il maggior numero di fantasmi.

--- task ---

Crea una nuova variabile chiamata 'tempo'.

--- /task ---

--- task ---

Puoi aggiungere un timer al tuo sfondo per dare al tuo giocatore solo 10 secondi per catturare quanti più fantasmi possibile?

Il tuo timer dovrebbe:

+ Partire da 10 secondi
+ Contare alla rovescia ogni secondo

Il gioco dovrebbe interrompersi quando il timer raggiunge lo 0.

--- hints ---
 --- hint --- `quando si clicca sulla bandiera verde`{:class="block3events"}, la variabile `tempo`{:class="block3variables"} dovrebbe essere `impostata su 10`{:class="block3variables"}. Dovrebbe quindi `cambiare di -1`{:class="block3variables"} ogni secondo `fino a quando non raggiunge 0`{:class="block3control"}.
--- /hint ---
 --- hint --- Qui ci sono i blocchi di codice che ti serviranno: ![sprite del fantasma](images/ghost-backdrop.png)

```blocks3
stop [tutto]

< [ ] = [ ] >

set [tempo v] to [10]

change [tempo v] by (-1)

(tempo)

wait (1) seconds

repeat until < >
end

when flag clicked

```

--- /hint --- --- hint --- Ecco il codice che dovrai aggiungere per creare il timer:

![icona scenario](images/ghost-backdrop.png)

```blocks3
when flag clicked
set [tempo v] to [10]
repeat until < (tempo) = [0] >
wait (1) seconds
change [tempo v] by (-1)
end
stop [tutto]
```

--- /hint --- --- /hints ---

--- /task ---

--- task ---

Chiedi a un amico di provare il tuo gioco. Quanti punti possono segnare?

--- /task ---

Se il gioco è troppo facile, puoi:

+ Dare al giocatore meno tempo
+ Ridurre la frequenza con cui i fantasmi appaiono
+ Rimpicciolire i fantasmi

--- task ---

Prova il gioco un paio di volte fino a quando non sei soddisfatto del livello di difficoltà.

--- /task ---
